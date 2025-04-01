<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Ling Jin Portfolio</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f9f9f9;
      display: flex;
    }

    .sidebar {
      width: 250px;
      background-color: #fff;
      padding: 20px;
      border-right: 1px solid #ddd;
      position: fixed;
      height: 100%;
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
      margin-left: 250px;
      padding: 40px;
      padding-bottom: 100px;
      width: 100%;
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
      border-radius: 8px;
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

    @media (max-width: 768px) {
      body {
        flex-direction: column;
      }

      .sidebar {
        position: static;
        width: 100%;
        height: auto;
        border-right: none;
        border-bottom: 1px solid #ddd;
      }

      .content {
        margin-left: 0;
        padding: 20px;
      }

      .intro {
        flex-direction: column;
        align-items: center;
      }

      .intro img {
        height: auto;
        width: 100px;
      }
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

    <!-- Your projects go here -->
    <!-- Example project -->
    <div id="project1" class="project">
      <h2>Financial Analysis of College Degrees Using Python</h2>
      <p><a href="https://github.com/lingjin0725/Python" target="_blank">View on GitHub</a></p>
      <p>
        Analyzed the financial outcomes of various undergraduate degrees using data structures like Hash Tables and Binary Search Trees.
        Data was sourced from Kaggle. The hash table proved more efficient, helping inform students about educational ROI.
      </p>
      <img src="https://github.com/user-attachments/assets/d4282b7b-a1ba-4112-8dbd-cd5d4015229f" alt="Financial Analysis Screenshot" />
    </div>

    <!-- Add other project sections below as already provided -->
  </div>
</body>
</html>
