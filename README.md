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

<!-- Insights & Findings -->
<h4>Insights & Findings</h4>
<ul>
  <li>Chemical Engineering emerged as the most financially rewarding major, with the highest mid-career median salary of $107,000.</li>
  <li>The hash table provided near-instant access to salary data regardless of dataset size. Its constant time complexity (O(1)) remained efficient as the dataset grew.</li>
  <li>The binary search tree (BST) allowed for an ordered view of salaries and degrees, enabling ranked comparisons. However, its performance slowed with larger or unbalanced datasets due to logarithmic time complexity (O(log n)).</li>
  <li>For tasks focused on finding a maximum value, hash tables proved faster and simpler than BSTs. BSTs may still be useful when ordered or range-based queries are required.</li>
  <li>Implementing both data structures helped illustrate the trade-offs between speed and order in solving real-world problems.</li>
  <li>Data cleaning steps such as removing currency symbols, filtering columns, and validating numeric values were essential to ensuring accurate results.</li>
</ul>

<p>
  ➤ View the full <a href="https://github.com/lingjin0725/Python" target="_blank">Python project on GitHub</a> for code, implementation details, and runtime comparisons.
</p>










<!-- Updated: Study Time vs GPA -->
<div class='tableauPlaceholder' id='vizStudyTimeGPA' style='width: 100%; margin: 30px 0;'>
  <object class='tableauViz' style='width: 100%; height: 700px;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>
    <param name='embed_code_version' value='3'/>
    <param name='site_root' value=''/>
    <param name='name' value='Studentsstudying10hoursweekperformed1520betteronaverage_/Sheet1'/>
    <param name='tabs' value='no'/>
    <param name='toolbar' value='yes'/>
    <param name='animate_transition' value='yes'/>
    <param name='display_static_image' value='yes'/>
    <param name='display_spinner' value='yes'/>
    <param name='display_overlay' value='yes'/>
    <param name='display_count' value='yes'/>
    <param name='language' value='en-US'/>
  </object>
</div>

<!-- Updated: Parent's Education vs GPA -->
<div class='tableauPlaceholder' id='vizParentsEducation' style='width: 100%; margin: 30px 0;'>
  <object class='tableauViz' style='width: 100%; height: 700px;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>
    <param name='embed_code_version' value='3'/>
    <param name='site_root' value=''/>
    <param name='name' value='ParentsEducationvsAverageGPA/Sheet12'/>
    <param name='tabs' value='no'/>
    <param name='toolbar' value='yes'/>
    <param name='animate_transition' value='yes'/>
    <param name='display_static_image' value='yes'/>
    <param name='display_spinner' value='yes'/>
    <param name='display_overlay' value='yes'/>
    <param name='display_count' value='yes'/>
    <param name='language' value='en-US'/>
  </object>
</div>

<!-- Updated: Attendance vs GPA -->
<div class='tableauPlaceholder' id='vizAttendanceGPA' style='width: 100%; margin: 30px 0;'>
  <object class='tableauViz' style='width: 100%; height: 700px;'>
    <param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F'/>
    <param name='embed_code_version' value='3'/>
    <param name='site_root' value=''/>
    <param name='name' value='AttendancevsGPA/Sheet14'/>
    <param name='tabs' value='no'/>
    <param name='toolbar' value='yes'/>
    <param name='animate_transition' value='yes'/>
    <param name='display_static_image' value='yes'/>
    <param name='display_spinner' value='yes'/>
    <param name='display_overlay' value='yes'/>
    <param name='display_count' value='yes'/>
    <param name='language' value='en-US'/>
  </object>
</div>

<script type='text/javascript' src='https://public.tableau.com/javascripts/api/viz_v1.js'></script>


