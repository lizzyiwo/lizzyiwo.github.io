<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Elizabeth Williams | Data Analyst</title>

<style>
body {
  font-family: Arial, sans-serif;
  background: #ffffff;
  color: #333;
  margin: 0;
}
header {
  background: #f4f4f4;
  text-align: center;
  padding: 50px 20px;
}
section {
  max-width: 900px;
  margin: auto;
  padding: 30px 20px;
}
h1, h2, h3 {
  color: #222;
}
.project {
  border: 1px solid #ddd;
  padding: 20px;
  margin-top: 20px;
  border-radius: 8px;
}
img {
  width: 100%;
  margin-top: 15px;
  border-radius: 6px;
}
.skills span {
  display: inline-block;
  background: #eee;
  padding: 8px 12px;
  margin: 5px;
  border-radius: 6px;
  font-size: 14px;
}
footer {
  text-align: center;
  padding: 20px;
  background: #f4f4f4;
  margin-top: 40px;
}
</style>

</head>
<body>

<header>
  <h1>Elizabeth Williams</h1>
  <p>Data Analyst transforming raw data into clear, actionable insights.</p>
</header>

<section>
  <h2>About Me</h2>
  <p>
    I specialize in analyzing datasets, building dashboards, and presenting insights that support business decisions. My work focuses on Excel analytics, data cleaning, and visualization for performance tracking and trend discovery.
  </p>
</section>

<section>
  <h2>Projects</h2>

  <div class="project">
    <h3>Edmotion Pod 01 Tasks Superstore Sales Analysis</h3>

    <p><strong>Project Summary:</strong>
    Conducted a full sales performance analysis using the Superstore dataset. Built interactive dashboards, cleaned raw data with Power Query, and used PivotTables to evaluate trends across regions, categories, and customer segments.
    </p>

    <p><strong>Tools Used:</strong> Excel · Power Query · PivotTables · Dashboard Design</p>

    <!-- Screenshots -->
    <img src="screenshots/Dashboard.png" alt="Dashboard Overview">
    <img src="screenshots/KPI.png" alt="KPI Section">
    <img src="screenshots/Charts.png" alt="Charts Section">

    <p><strong>Key Insights:</strong></p>
    <ul>
      <li>Total sales reached 1,099,862 across 5,009 orders.</li>
      <li>Technology generated the highest profit.</li>
      <li>West region recorded the strongest revenue.</li>
      <li>Consumer segment produced the largest sales share.</li>
    </ul>

    <p>
      <a href="https://github.com/lizzyiwo/superstore-sales-analysis" target="_blank">
      View Full Project Repository
      </a>
    </p>
  </div>

</section>

<section>
  <h2>Toolkit</h2>
  <div class="skills">
    <span>Excel</span>
    <span>Power Query</span>
    <span>PivotTables</span>
    <span>Dashboards</span>
    <span>Data Cleaning</span>
    <span>Visualization</span>
    <span>GitHub</span>
  </div>
</section>

<section>
  <h2>Contact</h2>
  <p>Email: lizzyiwo@gmail.com</p>
  <p>LinkedIn: <a href="https://www.linkedin.com/in/elizabeth-williams50">linkedin.com/in/elizabeth-williams50</a></p>
  <p>GitHub: <a href="https://github.com/lizzyiwo">github.com/lizzyiwo</a></p>
</section>

<footer>
  <p>© <span id="year"></span> Elizabeth Williams</p>
</footer>

<script>
document.getElementById("year").textContent = new Date().getFullYear();
</script>

</body>
</html>
