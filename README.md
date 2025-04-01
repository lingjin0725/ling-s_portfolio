<div style="display: flex; align-items: flex-start; gap: 20px;">
  <img src="IMG_2021.JPG" alt="Ling Jin" style="width: 160px; height: 200px; object-fit: cover; border: none;" />

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
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      height: 100vh;
      overflow: hidden;
    }

    .sidebar {
      width: 250px;
      background-color: #f7f7f7;
      padding: 20px;
      border-right: 1px solid #ccc;
      overflow-y: auto;
    }

    .sidebar h2 {
      font-size: 1.2em;
      margin-bottom: 10px;
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

    .profile {
      margin-bottom: 30px;
    }

    .profile img {
      width: 120px;
      border-radius: 8px;
    }

    .links a {
      margin-right: 15px;
      color: #0073e6;
      text-decoration: none;
    }

    .project img {
      max-width: 100%;
      border-radius: 8px;
      margin-top: 10px;
    }

    .sidebar a.active {
      font-weight: bold;
      color: #0073e6;
    }
  </style>
</head>
<body>

  <div class="sidebar">
    <div class="profile">
      <img src="images/profile.jpg" alt="Ling Jin" />
      <h2>Ling Jin</h2>
      <p style="font-size: 0.9em;">
        Data Analytics @ WSU • Turning data into insights • Visual storyteller
      </p>
      <div class="links">
        <a href="#">Resume</a>
        <a href="https://www.linkedin.com/in/lingjin0725/" target="_blank">LinkedIn</a>
        <a href="https://github.com/lingjin0725" target="_blank">GitHub</a>
      </div>
    </div>
    <hr />
    <a href="#" onclick="showProject('proj1', this)">🧠 NLP Project</a>
    <a href="#" onclick="showProject('proj2', this)">📊 Dashboard Analysis</a>
    <a href="#" onclick="showProject('proj3', this)">🤖 ML Model</a>
  </div>

  <div class="content">
    <div id="proj1" class="project active">
      <h2>🧠 NLP Project</h2>
      <p>Built an NLP pipeline for sentiment analysis on customer reviews.</p>
      <a href="https://github.com/lingjin0725/nlp_project" target="_blank">View Project</a>
      <img src="images/nlp_project.png" alt="NLP Project Screenshot" />
    </div>

    <div id="proj2" class="project">
      <h2>📊 Dashboard Analysis</h2>
      <p>Created interactive dashboards using Tableau to analyze sales data.</p>
      <a href="https://public.tableau.com/" target="_blank">View Dashboard</a>
      <img src="images/dashboard.png" alt="Dashboard Screenshot" />
    </div>

    <div id="proj3" class="project">
      <h2>🤖 ML Model</h2>
      <p>Trained and evaluated a classification model with 90% accuracy.</p>
      <a href="https://github.com/lingjin0725/ml_model" target="_blank">View Project</a>
      <img src="images/ml_model.png" alt="ML Model Screenshot" />
    </div>
  </div>

  <script>
    function showProject(id, el) {
      document.querySelectorAll('.project').forEach(p => p.classList.remove('active'));
      document.getElementById(id).classList.add('active');

      document.querySelectorAll('.sidebar a').forEach(a => a.classList.remove('active'));
      if (el) el.classList.add('active');
    }
  </script>

</body>
</html>

