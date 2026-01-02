# 📊 Day 6 – ETL Process & Power BI Architecture

## 📌 Session Overview
In Day 6, we shift focus from SQL to Data Integration and Business Intelligence (BI) concepts that are essential for every Data Analyst. This session introduces the ETL process, commonly used ETL tools, and provides a clear understanding of Microsoft Power BI architecture and datasets.

This session helps in understanding how data flows from source systems to dashboards, building a strong conceptual foundation before starting hands-on Power BI reporting.

---

## 🔁 ETL Process

ETL stands for Extract, Transform, Load. It is a process used to move data from multiple source systems into a centralized system for analysis and reporting.

### 1️⃣ Extract
- Data is collected from various sources
- Examples:
  - Databases (SQL Server, MySQL)
  - Excel files
  - CSV files
  - Web APIs
  - Cloud platforms

### 2️⃣ Transform
- Data is cleaned and prepared for analysis
- Includes:
  - Removing duplicates
  - Handling missing values
  - Changing data types
  - Filtering data
  - Creating calculated columns
  - Merging datasets

### 3️⃣ Load
- Transformed data is loaded into:
  - Data warehouses
  - Power BI datasets
  - Reporting systems

---

## 🛠️ Common ETL Tools
- SQL Server Integration Services (SSIS)
- Informatica
- Talend
- Apache Airflow
- Azure Data Factory
- Power BI Power Query

---

## 🧠 MS Power BI Architecture

Power BI architecture explains how data flows from source systems to dashboards and reports.

---

## 🔗 Power BI Architecture Components

### 1️⃣ Data Sources
- SQL Server
- Excel
- CSV
- Web APIs
- Cloud services

---

### 2️⃣ Power BI Desktop
- Used to:
  - Connect to data sources
  - Transform data using Power Query
  - Create data models
  - Build reports and visualizations

---

### 3️⃣ Power BI Service
- Cloud-based platform
- Used for:
  - Publishing reports
  - Creating dashboards
  - Sharing reports
  - Scheduling data refresh

---

### 4️⃣ Delivery
- Reports are delivered to users via:
  - Web browser
  - Power BI mobile app
  - Embedded dashboards
  - Email subscriptions

---

### 5️⃣ Power BI Report Server
- On-premises Power BI solution
- Used when cloud usage is restricted
- Data remains within organization servers

---

## 🔄 Power BI Data Flow

Data Sources  
↓  
Power BI Desktop  
↓  
Power BI Service  
↓  
Dashboards & Reports  
↓  
End Users  

---

## 🎯 Key Takeaways
- ETL is the backbone of data analytics
- Power BI uses ETL internally via Power Query
- Understanding architecture helps in building efficient and scalable reports

