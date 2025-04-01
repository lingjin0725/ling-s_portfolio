<div style="display: flex; align-items: flex-start; gap: 20px;">
  <img src="IMG_9900.png" alt="Ling Jin" style="width: 160px; height: 200px; object-fit: cover; border: none;" />

  <div>
    <h2>Ling Jin</h2>
    <p>
      I’m currently studying Data Analytics at Washington State University, with a strong interest in turning data into insights.
      I enjoy uncovering patterns, building intuitive visualizations, and helping drive data-informed decisions.
    </p>
    <p style="margin-top: 10px;">
      <a href="Resume.pdf" target="_blank">Resume</a> |
      <a href="https://www.linkedin.com/in/lingjin0913/" target="_blank">LinkedIn</a> |
      <a href="https://github.com/lingjin0725" target="_blank">GitHub</a>
    </p>
  </div>
</div>





<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Ling Jin Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: sans-serif;
      display: flex;
      height: 100vh;
    }

    .sidebar {
      width: 250px;
      background-color: #f8f8f8;
      padding: 20px;
      overflow-y: auto;
      border-right: 1px solid #ccc;
    }

    .sidebar a {
      display: block;
      margin: 10px 0;
      color: #333;
      text-decoration: none;
    }

    .sidebar a:hover {
      font-weight: bold;
    }

    .content {
      flex: 1;
      padding: 40px;
      overflow-y: auto;
    }

    .project {
      display: none;
    }

    .project.active {
      display: block;
    }
  </style>
</head>
<body>
  <div class="sidebar">
    <a href="#" onclick="showProject('proj1')">🧠 NLP Project</a>
    <a href="#" onclick="showProject('proj2')">📊 Dashboard Analysis</a>
    <a href="#" onclick="showProject('proj3')">🤖 ML Model</a>
    <!-- Add more project links -->
  </div>

  <div class="content">
    <div id="proj1" class="project active">
      <h2>NLP Project</h2>
      <p>Description of the project goes here.</p>
      <img src="images/nlp_project.png" alt="NLP Project Screenshot" width="100%" />
    </div>

    <div id="proj2" class="project">
      <h2>Dashboard Analysis</h2>
      <p>Here's what I did with Power BI/Tableau...</p>
      <img src="images/dashboard.png" alt="Dashboard Screenshot" width="100%" />
    </div>

    <div id="proj3" class="project">
      <h2>ML Model</h2>
      <p>ML details and evaluation metrics.</p>
      <img src="images/ml_model.png" alt="Model Screenshot" width="100%" />
    </div>
  </div>

  <script>
    function showProject(id) {
      document.querySelectorAll('.project').forEach(p => p.classList.remove('active'));
      document.getElementById(id).classList.add('active');
    }
  </script>
</body>
</html>
