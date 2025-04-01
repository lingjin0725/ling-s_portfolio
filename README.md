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
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ling Jin Portfolio</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      height: 100vh;
      overflow: hidden;
      background-color: #f9f9f9;
    }

    .sidebar {
      width: 260px;
      background-color: #ffffff;
      padding: 20px;
      border-right: 1px solid #ddd;
      position: fixed;
      height: 100vh;
      overflow-y: auto;
    }

    .sidebar a {
      display: block;
      margin: 10px 0;
      color: #333;
      text-decoration: none;
      transition: all 0.2s;
    }

    .sidebar a:hover,
    .sidebar a.active {
      color: #0056b3;
      font-weight: bold;
    }

    .content {
      margin-left: 260px;
      padding: 40px;
      overflow-y: auto;
      flex: 1;
    }

    .intro {
      display: flex;
      align-items: flex-start;
      gap: 20px;
      margin-bottom: 40px;
    }

    .intro img {
      width: 160px;
      height: 200px;
      object-fit: cover;
    }

    .links a {
      margin-right: 10px;
      color: #0073e6;
      text-decoration: none;
    }

    .project {
      margin-bottom: 60px;
      animation: fadeIn 0.6s ease-in;
    }

    .project img {
      max-width: 100%;
      margin: 10px 0;
      border-radius: 8px;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(10px); }
      to { opacity: 1; transform: translateY(0); }
    }

    h2 {
      color: #333;
    }

    p {
      line-height: 1.6;
      color: #444;
    }
  </style>
</head>
<body>
  <div class="sidebar">
    <a href="#project1">Financial Analysis</a>
    <a href="#project2">Flight Delays & Viz</a>
    <a href="#project3">Student Performance</a>
    <a href="#project4">Car Rental System</a>
  </div>

  <div class="content">
    <div class="intro">
      <img src="IMG_2021.JPG" alt="Ling Jin" />
      <div>
        <h2>Ling Jin</h2>
        <p>
          I’m currently studying Data Analytics at Washington State University, with a strong interest in turning data into insights.
          I enjoy uncovering patterns, building intuitive visualizations, and helping drive data-informed decisions.
        </p>
        <p class="links">
          <a href="Resume.pdf" target="_blank">Resume</a>
          <a href="https://www.linkedin.com/in/lingjin0913/" target="_blank">LinkedIn</a>
          <a href="https://github.com/lingjin0725" target="_blank">GitHub</a>
        </p>
      </div>
    </div>

    <div id="project1" class="project">
      <h2>Financial Analysis of College Degrees Using Python</h2>
      <p><a href="https://github.com/lingjin0725/Python" target="_blank">View on GitHub</a></p>
      <p>Analyzed the financial outcomes of various undergraduate degrees using data structures like Hash Tables and Binary Search Trees. Data was sourced from Kaggle. The hash table proved more efficient, helping inform students about educational ROI.</p>
      <img src="https://github.com/user-attachments/assets/d4282b7b-a1ba-4112-8dbd-cd5d4015229f" alt="Financial Analysis Screenshot">
    </div>

    <div id="project2" class="project">
      <h2>Flight Delays and Network Analysis with High Dimensional Visualization in R</h2>
      <p><a href="https://github.com/lingjin0725/nycflights13" target="_blank">View on GitHub</a></p>
      <p>Explored NYC flight delays using the nycflights13 dataset. Utilized Plotly for interactive visualizations and igraph for network analysis. Demonstrated complex modeling and interpretation of high-dimensional data.</p>
      <img src="https://github.com/user-attachments/assets/9c3bd060-5849-47d0-a316-01a423566341" alt="Flight Delay Screenshot">
      <img src="https://github.com/user-attachments/assets/bd5b29f7-a38b-452b-8ba9-a189877e183e" alt="Network Graph">
      <img src="https://github.com/user-attachments/assets/f0b5d0ef-758f-4b94-a901-c66e6a8dd536" alt="Plotly Screenshot">
    </div>

    <div id="project3" class="project">
      <h2>Higher Education Students Performance Evaluation Using R</h2>
      <p><a href="https://github.com/lingjin0725/R" target="_blank">View on GitHub</a></p>
      <p>Used regression and classification models to explore student GPA predictors from the UCI dataset. Techniques included Linear Regression, Random Forest, Logistic Regression, and KNN. Key factors like socio-economic status and study habits were visualized.</p>
      <img src="https://github.com/user-attachments/assets/5a9c7d91-5b41-406e-a1f1-11961732b75f" alt="Student Perf Screenshot">
      <img src="https://github.com/user-attachments/assets/abf7c6f3-1d8e-4fd0-bedf-fb4af7a9d071" alt="Model Visualization">
      <img src="https://github.com/user-attachments/assets/87f405a2-73d6-4e67-9679-cc1b84545c2e" alt="Feature Importance">
      <img src="https://github.com/user-attachments/assets/cd9979e2-624d-432c-a26a-b057f53472db" alt="Additional Chart">
    </div>

    <div id="project4" class="project">
      <h2>Car Rental Management System Using Java</h2>
      <p><a href="https://github.com/lingjin0725/Java" target="_blank">View on GitHub</a></p>
      <p>Developed a Java-based car rental system with OOP principles, GUI interface, and dynamic inventory management via ArrayLists. Designed for real-time vehicle tracking and customer processing.</p>
    </div>

  </div>
</body>
</html>


