# 📊 Pharma Incentive Calculation – Data Engineering Project

## 🚀 Overview
End-to-end Data Engineering project to calculate employee incentives using Azure and Databricks with Medallion Architecture.

---

## 🏗️ Architecture
Medallion Architecture:
**Bronze → Silver → Gold**

- Bronze: Raw data ingestion (Delta)
- Silver: Data cleaning & validation
- Gold: Business logic (incentive calculation)

---

## ⚙️ Tech Stack
- Azure Data Lake Gen2
- Azure Databricks (PySpark)
- Delta Lake
- Azure Data Factory (Pipelines, Triggers)
- Unity Catalog
- Azure Logic Apps (Alerts)
- Power BI

---

## 🔄 Pipeline Flow
1. Ingest data via ADF  
2. Store in Bronze layer  
3. Clean & transform in Silver  
4. Calculate incentives in Gold  
5. Visualize in Power BI  

---

## 🔁 Automation
- ADF pipelines with schedule & event triggers  
- Databricks Jobs & Workflows for ETL automation  

---

## 📦 Data Lake Structure