🚀 Azure Data Engineering Project
This project demonstrates an end-to-end data engineering workflow on Microsoft Azure, involving:

Data ingestion from a website

ETL using Azure Data Factory and Azure Databricks

Data storage in Azure Data Lake

Analysis using SQL

📌 Tech Stack
Azure Data Lake Storage Gen2

Azure Data Factory

Azure Databricks (PySpark)

Azure SQL Database / Serverless SQL Pool

APIs / Web scraping (for data source)

🗂️ Project Workflow
1. 🔗 Ingest Data from Website
Data source: Public data/API from website

Method: Use ADF pipeline with HTTP connector

Activity: Copy Activity to transfer data to Azure Data Lake Storage (ADLS)

2. 🔧 Azure Data Factory Setup
Created Linked Services:

HTTP (Source)

ADLS (Sink)

Defined Dynamic Datasets for flexible schema handling

Designed ETL Pipeline with:

Copy Activity to extract and load

Triggered manually or via schedule

3. 🧪 Data Transformation (Azure Databricks)
Mounted Azure Data Lake Storage in Databricks

Read raw data using PySpark

Performed transformations:

Schema validation

Null handling

Date parsing & filtering

Aggregations / Feature engineering

Wrote transformed data back to ADLS

4. 📊 Data Analysis
   Using databricks
