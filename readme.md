# 📊 Pharma Incentive Calculation – Data Engineering Project

## 🚀 Overview
This project builds an end-to-end data pipeline to calculate employee incentives for a pharma company using Azure and Databricks. It solves the need for automated, accurate, and scalable incentive calculation from raw sales data. Key features include Medallion architecture, Delta Lake incremental processing, automated pipelines with triggers, and real-time monitoring using Logic Apps.

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
- Azure Logic Apps (Email-Alerts)
- Power BI

---

## 🔄 Pipeline Flow
1. Ingest data via Azure to databricks  
2. Store in Bronze layer  
3. Clean & transform in Silver  
4. Calculate incentives in Gold  
5. Visualize in Power BI  

---

## 🔁 Automation
- Azure LogicApp & event triggers  
- Databricks Jobs & Workflows for ETL automation  

---

## 📦 Data Lake Structure
/pharma-data/
bronze/
silver/
gold/



## 🧠 Key Concepts
- Medallion Architecture  
- Delta Lake (MERGE, UPSERT, ACID)  
- Incremental Processing  
- Data Quality Checks  
- Schema Evolution  
- Managed & External Tables  
- Unity Catalog  

---

## 🔔 Monitoring
- Pipeline logs tracking  
- Real-time alerts using Logic Apps  

---

## 📈 Output
- Incentive Calculation  
- Sales Insights Dashboard  

---

## 💡 Highlights
✔ Scalable pipeline  
✔ Automated workflows  
✔ Real-time monitoring  
✔ Industry-standard design  