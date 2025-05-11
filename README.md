<div style="display: flex; align-items: flex-start; gap: 20px; margin-bottom: 30px;">
  <img src="IMG_2022.png" alt="Ling Jin" style="width: 160px; height: 200px; object-fit: cover; border-radius: 8px;" />
  <div>
    <h2>Ling Jin</h2>
    <p>
      I’m currently studying Data Analytics at Washington State University, with a strong interest in turning data into insights. I enjoy uncovering patterns, building intuitive visualizations, and helping drive data-informed decisions.
    </p>
    <p style="margin-top: 10px;">
      <a href="Resume.pdf" target="_blank">Resume</a> |
      <a href="https://www.linkedin.com/in/lingjin0913/" target="_blank">LinkedIn</a> |
      <a href="https://github.com/lingjin0725" target="_blank">GitHub</a>
    </p>
  </div>
</div>





<h2 id="project1">Project 1: College ROI Analysis Using Python & Data Structures</h2>
<p>
  This project, completed for my Data Structures and Algorithms course, explores the return on investment (ROI) of various undergraduate degrees by analyzing starting and mid-career salaries. Using Python, I implemented Hash Tables and Binary Search Trees to identify the most financially rewarding majors and compare performance efficiency. I then visualized the results in Tableau to provide an intuitive, interactive comparison.
</p>

<ul>
  <li>Dataset: Kaggle’s “Degrees That Pay Back”</li>
  <li>Techniques: Hash Table (O(1)) for fast lookups and BST (O(log n)) for ordered traversal</li>
  <li>Insight: Chemical Engineering had the highest ROI. Hash Table proved more efficient for this task.</li>
</ul>

<!-- Tableau Interactive Visualization Embed -->
<div class='tableauPlaceholder' id='vizDegreePayback' style='position: relative; margin: 30px 0;'>
  <noscript>
    <a href='https://public.tableau.com/views/DegreePaybackComparisonStartingvsMid-CareerSalary/Sheet1'>
      <img alt='Degree Payback Comparison' src='https://public.tableau.com/static/images/De/DegreePaybackComparisonStartingvsMid-CareerSalary/Sheet1/1.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz' style='display:none;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='DegreePaybackComparisonStartingvsMid-CareerSalary/Sheet1' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='yes' />
    <param name='static_image' value='https://public.tableau.com/static/images/De/DegreePaybackComparisonStartingvsMid-CareerSalary/Sheet1/1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
    <param name='language' value='en-US' />
  </object>
</div>
<script type='text/javascript'>
  var divElement = document.getElementById('vizDegreePayback');
  var vizElement = divElement.getElementsByTagName('object')[0];
  vizElement.style.width = '100%';
  vizElement.style.height = (divElement.offsetWidth * 0.75) + 'px';
  var scriptElement = document.createElement('script');
  scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
  vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>

<!-- Performance Comparison Chart -->
<h4>Performance Comparison: Hash Table vs. BST</h4>
<p>
  To evaluate algorithm efficiency, I recorded the runtime for both data structures on datasets of different sizes. As shown below, the hash table maintained consistent performance (O(1)), while the BST showed increased runtime as size grew (O(log n)). This helped validate the use of hashing for optimal speed in this project.
</p>

<img src="performance_chart.png" 
     alt="Performance Comparison: Hash Table vs. BST" 
     style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 6px; margin-top: 15px;" />

<p>
  ➤ View the full <a href="https://github.com/lingjin0725/Python" target="_blank">Python project on GitHub</a> for code, implementation details, and runtime comparisons.
</p>










<h2 id="project2">Project 2: Student Performance Prediction Using R & Machine Learning Models</h2>

<p>
  This project was completed as part of my <strong>Statistical Modeling course</strong>. I analyzed the academic performance of higher education students using machine learning models to predict GPA and uncover influential factors. The dataset was sourced from the <a href="https://archive.ics.uci.edu/dataset/856/higher+education+students+performance+evaluation" target="_blank">UCI Machine Learning Repository</a>.
</p>

<ul>
  <li><strong>Goal:</strong> Predict student GPA and identify key socio-economic, academic, and behavioral variables that influence performance.</li>
  <li><strong>Tools Used:</strong> R (tidyverse, ggplot2, caret), Tableau for interactive visualization</li>
  <li><strong>Algorithms Applied:</strong> Linear Regression, Logistic Regression, Random Forest, K-Nearest Neighbors (KNN)</li>
  <li><strong>Key Techniques:</strong> Data cleaning, correlation analysis, model tuning, feature importance evaluation, and performance metrics (RMSE, accuracy)</li>
</ul>

<div style="margin: 30px 0;">
  <img src="https://github.com/user-attachments/assets/5a9c7d91-5b41-406e-a1f1-11961732b75f" 
       alt="Correlation Heatmap" 
       style="max-width: 100%; border-radius: 8px; margin-bottom: 15px;" />

  <img src="https://github.com/user-attachments/assets/abf7c6f3-1d8e-4fd0-bedf-fb4af7a9d071" 
       alt="GPA Distribution by Study Time" 
       style="max-width: 100%; border-radius: 8px; margin-bottom: 15px;" />

  <img src="https://github.com/user-attachments/assets/87f405a2-73d6-4e67-9679-cc1b84545c2e" 
       alt="Model Accuracy Comparison" 
       style="max-width: 100%; border-radius: 8px; margin-bottom: 15px;" />

  <img src="https://github.com/user-attachments/assets/cd9979e2-624d-432c-a26a-b057f53472db" 
       alt="Feature Importance Plot - Random Forest" 
       style="max-width: 100%; border-radius: 8px;" />
</div>

<h4>🔍 Insights & Findings</h4>
<ul>
  <li><strong>Parental education level</strong>, <strong>weekly study time</strong>, and <strong>student absences</strong> were the strongest predictors of GPA.</li>
  <li>Random Forest achieved the highest prediction accuracy (~82%), outperforming both linear and logistic regression models.</li>
  <li>Students with consistent study habits and strong family support showed a significant GPA advantage over peers lacking these factors.</li>
  <li>Visualization of study time vs GPA revealed that students studying ≥10 hours/week performed 15–20% better on average.</li>
  <li>Feature importance analysis validated that behavioral factors can be just as predictive as academic background.</li>
</ul>

<p>
  ➤ View the full analysis and source code on <a href="https://github.com/lingjin0725/R" target="_blank">GitHub</a>.
</p>






