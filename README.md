<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Azure Data Engineering Project</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      max-width: 900px;
      margin: auto;
      padding: 40px;
      background-color: #f8f9fa;
    }
    h1, h2, h3 {
      color: #0a66c2;
    }
    code, pre {
      background-color: #eee;
      padding: 5px;
      border-radius: 4px;
    }
    .folder-structure {
      background: #f1f1f1;
      padding: 10px;
      font-family: monospace;
      border-left: 4px solid #0a66c2;
    }
  </style>
</head>
<body>

  <h1>🚀 Azure Data Engineering Project</h1>

  <p>This project demonstrates an end-to-end data engineering workflow on <strong>Microsoft Azure</strong>, involving:</p>
  <ul>
    <li>Data ingestion from a website</li>
    <li>ETL using <strong>Azure Data Factory</strong> and <strong>Azure Databricks</strong></li>
    <li>Data storage in <strong>Azure Data Lake</strong></li>
    <li>Analysis using <strong>SQL</strong></li>
  </ul>

  <h2>📌 Tech Stack</h2>
  <ul>
    <li>Azure Data Lake Storage Gen2</li>
    <li>Azure Data Factory</li>
    <li>Azure Databricks (PySpark)</li>
    <li>Azure SQL Database / Synapse SQL</li>
    <li>APIs / Web Scraping (data source)</li>
  </ul>

  <h2>🗂️ Project Workflow</h2>

  <h3>1. 🔗 Ingest Data from Website</h3>
  <ul>
    <li>Source: Public API / website</li>
    <li>Used <strong>Azure Data Factory HTTP connector</strong></li>
    <li><strong>Copy Activity</strong> to move data to Azure Data Lake (ADLS)</li>
  </ul>

  <h3>2. 🔧 Azure Data Factory Setup</h3>
  <ul>
    <li>Created <strong>Linked Services</strong> for HTTP and ADLS</li>
    <li>Built <strong>Dynamic Datasets</strong> for flexibility</li>
    <li>Designed <strong>Data Pipelines</strong> with manual and trigger-based execution</li>
  </ul>

  <h3>3. 🧪 Data Transformation using Databricks</h3>
  <ul>
    <li>Mounted ADLS into Databricks workspace</li>
    <li>Read raw data with <strong>PySpark</strong></li>
    <li>Performed transformations (cleaning, filtering, aggregation)</li>
    <li>Wrote transformed data back to ADLS (curated zone)</li>
  </ul>

  <h3>4. 📊 Data Analysis</h3>
  <ul>
    <li>Databricks / Synapse</strong></li>

  </ul>


</body>
</html>
