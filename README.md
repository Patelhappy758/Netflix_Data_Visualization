<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Netflix Data Visualization</title>
  <style>
    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0f0f0f;
      color: #f5f5f5;
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }
    header {
      text-align: center;
      padding: 2rem;
      background: linear-gradient(135deg, #e50914, #b20710);
      color: white;
    }
    header h1 {
      font-size: 2.5rem;
      margin: 0;
    }
    section {
      padding: 2rem;
      max-width: 900px;
      margin: auto;
    }
    h2 {
      color: #e50914;
      border-bottom: 2px solid #e50914;
      padding-bottom: 5px;
      margin-bottom: 1rem;
    }
    ul li {
      margin: 0.5rem 0;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin: 1rem 0;
    }
    table, th, td {
      border: 1px solid #444;
    }
    th, td {
      padding: 0.8rem;
      text-align: left;
    }
    th {
      background: #e50914;
      color: white;
    }
    .btn {
      display: inline-block;
      margin-top: 1rem;
      padding: 0.6rem 1.2rem;
      background: #e50914;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      transition: background 0.3s ease;
    }
    .btn:hover {
      background: #b20710;
    }
    code {
      background: #222;
      padding: 0.2rem 0.4rem;
      border-radius: 4px;
      color: #ffb347;
    }
    pre {
      background: #1a1a1a;
      padding: 1rem;
      border-radius: 8px;
      overflow-x: auto;
    }
    footer {
      text-align: center;
      padding: 1.5rem;
      margin-top: 2rem;
      background: #1a1a1a;
      color: #aaa;
    }
  </style>
</head>
<body>

  <header>
    <h1>📺 Netflix Data Visualization</h1>
    <p>A data-driven exploration of Netflix’s content catalog using Python & Matplotlib</p>
  </header>

  <section>
    <h2>🔍 Project Overview</h2>
    <ul>
      <li>📅 <b>Release Trends</b> → Number of shows released per year</li>
      <li>🌍 <b>Country Insights</b> → Top 10 countries by content volume</li>
      <li>🎬 <b>Content Type Comparison</b> → Movies vs. TV shows over time</li>
      <li>📈 <b>PDF & CDF Analysis</b> → Probability and cumulative distribution of releases</li>
    </ul>
  </section>

  <section>
    <h2>📊 Visualizations</h2>
    <table>
      <tr>
        <th>Visualization</th>
        <th>Description</th>
      </tr>
      <tr>
        <td>📅 Release Year vs. Number of Shows</td>
        <td>Scatter plot showing yearly content trends</td>
      </tr>
      <tr>
        <td>🌍 Top Countries by Content Volume</td>
        <td>Horizontal bar chart of top 10 countries</td>
      </tr>
      <tr>
        <td>🎬 Movies vs. TV Shows Over Time</td>
        <td>Dual line plots comparing release patterns</td>
      </tr>
      <tr>
        <td>📈 PDF & CDF of Releases</td>
        <td>Statistical view of distribution and accumulation</td>
      </tr>
    </table>
  </section>

  <section>
    <h2>📁 Dataset</h2>
    <p>📌 Dataset: <a href="https://www.kaggle.com/datasets/shivamb/netflix-shows" target="_blank" class="btn">Kaggle - Netflix Movies and TV Shows</a></p>
    <p><b>Steps:</b></p>
    <ol>
      <li>Download the CSV file from Kaggle</li>
      <li>Place it in the root directory of this repository</li>
      <li>Rename it to <code>netflix_titles.csv</code> (or update the notebook path)</li>
    </ol>
  </section>

  <section>
    <h2>🧠 Insights</h2>
    <ul>
      <li>🚀 Netflix’s content production <b>surged after 2015</b>, reflecting global expansion</li>
      <li>🇺🇸 <b>U.S., India, and the UK</b> dominate Netflix’s catalog</li>
      <li>📺 TV shows have seen a <b>sharper rise</b> in recent years compared to movies</li>
      <li>📈 <b>PDF & CDF plots</b> reveal peak release periods and distribution patterns</li>
    </ul>
  </section>

  <section>
    <h2>🛠️ Tools Used</h2>
    <ul>
      <li>🐍 Python (Pandas, Matplotlib)</li>
      <li>📓 Jupyter Notebook</li>
      <li>📂 Netflix Dataset (CSV format)</li>
    </ul>
  </section>

 
    
  <footer>
    <p>💡 Created with ❤️ by Happy</p>
  </footer>

</body>
</html>

