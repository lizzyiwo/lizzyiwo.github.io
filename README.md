<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Elizabeth Williams | Data Analyst</title>

<style>
body{
font-family: Arial, sans-serif;
margin:0;
background:#ffffff;
color:#333;
line-height:1.6;
}

header{
background:#f5f5f5;
text-align:center;
padding:60px 20px;
}

section{
max-width:900px;
margin:auto;
padding:40px 20px;
}

h1,h2,h3{
color:#222;
}

.project{
border:1px solid #ddd;
padding:20px;
margin-top:20px;
border-radius:8px;
}

img{
max-width:100%;
margin-top:15px;
border-radius:6px;
}

.skills span{
display:inline-block;
background:#eee;
padding:8px 12px;
margin:5px;
border-radius:6px;
font-size:14px;
}

footer{
text-align:center;
padding:30px;
background:#f5f5f5;
margin-top:40px;
}
</style>
</head>

<body>

<header>
<h1>Elizabeth Williams</h1>
<p>Data Analyst transforming raw data into clear business insights using Excel and dashboards.</p>
</header>

<section>
<h2>About</h2>
<p>
I am a data analyst focused on uncovering patterns that drive business decisions. I specialize in cleaning datasets, building dashboards, and presenting insights clearly using Excel, Power Query, and data visualization techniques.
</p>
</section>

<section>
<h2>Projects</h2>

<div class="project">

<h3>Edmotion Pod 01 Tasks Superstore Sales Analysis</h3>

<p><strong>Summary:</strong>
Analyzed retail sales data to evaluate performance across regions, categories, and customer segments using Excel dashboards and pivot analysis.
</p>

<p><strong>Tools Used:</strong>
Excel · Power Query · PivotTables · Dashboards
</p>

<img src="images/dashboard_overview.png" alt="Dashboard overview">

<img src="images/kpi_section.png" alt="KPI summary">

<img src="images/charts_section.png" alt="Charts section">

<p><strong>Key Insights:</strong></p>
<ul>
<li>Total sales reached 1,099,862 across 5009 orders.</li>
<li>Technology produced the highest profit at 70,158.</li>
<li>West region recorded the strongest sales at 332,444.</li>
<li>Consumer segment generated the most revenue at 558,251.</li>
</ul>

<p>
<a href="https://github.com/lizzyiwo/superstore-sales-analysis" target="_blank">
View Project Repository
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
<span>Data Cleaning</span>
<span>Dashboards</span>
<span>Visualization</span>
<span>GitHub</span>
</div>

</section>

<section>
<h2>Contact</h2>

<p>Email: lizzyiwo@gmail.com</p>
<p>LinkedIn: <a href="https://www.linkedin.com/in/elizabeth-williams50">www.linkedin.com/in/elizabeth-williams50</a></p>
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
