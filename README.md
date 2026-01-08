# 🚀 End-to-End Data Analytics Pipeline using Lakehouse & Power BI

## 📌 Project Overview
This project demonstrates a complete end-to-end data analytics pipeline, starting from raw CSV ingestion to automated reporting in Power BI using a Lakehouse architecture.

The solution leverages dataflows, a data warehouse, semantic modeling, and pipeline orchestration to ensure clean, transformed, and automatically refreshed data for reporting.

---

## 🏗️ Architecture Overview

CSV Files  
⬇  
Lakehouse  
⬇  
Dataflows (Transformation)  
⬇  
Data Warehouse  
⬇  
Views  
⬇  
Semantic Model  
⬇  
Power BI Report (Live Connection)  
⬇  
Pipeline Automation

---

## 🔧 Technologies Used
- Microsoft Fabric
- Power BI
- Lakehouse
- Dataflows (ETL)
- Data Warehouse
- Semantic Model
- CI/CD Pipelines

---

## 📂 Project Workflow

### 1️⃣ Workspace & Lakehouse Setup
- Created a dedicated workspace.
- Created a Lakehouse to store raw data.
- Imported multiple CSV files into the Lakehouse.

---

### 2️⃣ Data Transformation using Dataflows
- Created dataflows to perform transformations:
  - Data type corrections
  - Column renaming
  - Null value handling
  - Business logic implementation
- Loaded transformed data into the Data Warehouse.

---

### 3️⃣ Data Warehouse & Views
- Created structured tables in the Data Warehouse.
- Built SQL views on top of warehouse tables to:
  - Simplify reporting logic
  - Improve performance
  - Ensure semantic consistency

---

### 4️⃣ Semantic Model
- Created a semantic model using warehouse views.
- Defined relationships and measures.
- Optimized the model for Live Connection.

---

### 5️⃣ Power BI Report
- Created a Power BI report using Live Connection to the semantic model.
- Designed interactive visuals and dashboards.
- Published the report to the Power BI Service.

---

### 6️⃣ Pipeline Automation
- Created a pipeline to orchestrate the workflow.
- Configured dataflow refresh.
- Set up an on-success trigger to refresh the semantic model.
- Ensured automatic Power BI report updates when new data is ingested.

---

## 🔄 End-to-End Refresh Flow
1. New CSV files are added to the Lakehouse  
2. Dataflows refresh and transform data  
3. Data Warehouse tables and views are updated  
4. Semantic model refreshes automatically  
5. Power BI report reflects the latest data  

---

## ✅ Key Features
- Fully automated data refresh
- Scalable Lakehouse architecture
- Clean separation of raw, transformed, and semantic layers
- Live Power BI reporting
- Production-ready orchestration

---

## 📈 Business Value
- Eliminates manual refresh processes
- Ensures consistent and reliable reporting
- Reduces data latency
- Supports scalable analytics solutions


