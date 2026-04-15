# 🌍 End-to-End Earthquake Data Pipeline (Microsoft Fabric)

## 📖 Overview

This project showcases a modern **end-to-end data engineering pipeline** built using Microsoft Fabric. It processes real-time earthquake data using the **Medallion Architecture (Bronze, Silver, Gold layers)** and delivers actionable insights through interactive Power BI dashboards.

---

## 🎯 Problem Statement

Accessing and analyzing earthquake data in a structured and timely manner is critical for risk assessment and decision-making. However, raw data from APIs is often unstructured and not directly usable.

This project solves that problem by:

* Automating data ingestion
* Structuring and transforming raw data
* Enabling easy analysis through visualization

---

## 🏗️ Architecture

The pipeline follows the **Medallion Architecture**:

* **Bronze Layer** → Raw data ingestion from API
* **Silver Layer** → Data cleaning and transformation
* **Gold Layer** → Data enrichment and analytics-ready dataset
* **Power BI** → Data visualization
* **Data Factory** → Pipeline orchestration and automation

---

## ⚙️ Tech Stack

| Category        | Tools Used               |
| --------------- | ------------------------ |
| Data Platform   | Microsoft Fabric         |
| Data Ingestion  | Python, API              |
| Data Processing | Spark                    |
| Storage         | Lakehouse (Delta Tables) |
| Visualization   | Power BI                 |
| Orchestration   | Data Factory             |

---

## 🔄 Data Pipeline Flow

1. Extract earthquake data from external API
2. Store raw JSON data in Bronze layer
3. Transform data into structured format (Silver layer)
4. Enrich data for analysis (Gold layer)
5. Visualize insights using Power BI
6. Automate pipeline execution with Data Factory

---

## 🧱 Medallion Layers Explained

### 🟤 Bronze Layer (Raw Data)

* Stores raw API data without modification
* Ensures data traceability and auditability

---

### ⚪ Silver Layer (Cleaned Data)

* Cleans and filters raw data
* Converts JSON to structured Delta tables
* Extracts key fields like magnitude, time, and location

---

### 🟡 Gold Layer (Business-Level Data)

* Aggregates and enriches data
* Prepares dataset for reporting and analytics

---

## 📊 Visualization

Power BI dashboards provide:

* Earthquake frequency trends
* Magnitude distribution
* Location-based analysis

---

## 🔁 Automation

Using Data Factory:

* Pipeline runs automatically on schedule
* Ensures up-to-date data availability
* Reduces manual intervention

---

## 📸 Screenshots
<img width="1024" height="314" alt="image" src="https://github.com/user-attachments/assets/d4e44910-9b0d-418d-a966-df2c270f2063" />
* Architecture Diagram

* Data Pipeline Flow
<img width="1133" height="303" alt="image" src="https://github.com/user-attachments/assets/4dc69610-080f-4d05-8efa-163c25d82294" />

* Power BI Dashboard
<img width="1915" height="871" alt="image" src="https://github.com/user-attachments/assets/42f8e5f6-109c-41cc-b112-b75be92e4b19" />

---

## 🚀 Key Highlights

* End-to-end data pipeline implementation
* Real-world data engineering use case
* Scalable architecture using Fabric
* Automated workflow

---

## 🔮 Future Enhancements

* Real-time data streaming
* Advanced analytics (ML integration)
* Alert system for high-risk events

---

## 👨‍💻 Author

**Abhijeet Thosar**
Aspiring Data Engineer

