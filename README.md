# 🏠 Airbnb Data Warehouse & Business Intelligence

## 📌 Overview
This project implements a **Data Warehouse & Business Intelligence (BI) solution** using **SQL Server, SSIS, and Python**. The dataset is sourced from **Airbnb Open Data** and transformed into a structured **dimensional model** for analytics.

## 🚀 Features
- **Data Warehouse Design** (Star/Snowflake Schema)
- **ETL Development** using **SSIS**
- **Multiple Data Sources** (CSV, SQL Database)
- **Slowly Changing Dimensions (SCD Type 2)**
- **Fact Table with Accumulating Metrics**
- **BI Reporting & Aggregations**

## 🛠️ Tech Stack
- **SQL Server** (Data Warehouse)
- **SSIS** (ETL Development)
- **Python** (Data Preprocessing)
- **Kaggle Airbnb Dataset** ([Link](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata))
- **Power BI / SSAS** (Optional for Reporting)

## 🔧 Installation & Setup

### **1️⃣ Clone the Repository**
```bash
git clone https://github.com/Hari-2782/airbnb-data-warehouse.git
cd airbnb-data-warehouse
```
### **2️⃣ Set Up SQL Server**
Install SQL Server (any version)

Create a Data Warehouse Database

Run the provided SQL scripts to create tables

### **3️⃣ Prepare Data Sources**
Download the Airbnb dataset from Kaggle ([Link](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata))

Store files in /data/ directory

### **4️⃣ ETL Development with SSIS**
Open SQL Server Data Tools (SSDT)

Import the SSIS package

Configure data sources (CSV, SQL)

Run the ETL pipeline to load data

### **5️⃣ Run Queries & Reports**
Execute SQL queries for analytics

Optionally, use Power BI for visualization

### **📜 Data Warehouse Schema**
The dimensional model includes:

Fact Table: fact_airbnb_transactions

Dimensions: dim_host, dim_location, dim_property, dim_date

Slowly Changing Dimension: dim_host (SCD Type 2)

### **📺 Screen Shots**
![Screenshot 2025-05-10 163001](https://github.com/user-attachments/assets/fc250466-e6be-41e4-aa94-aebfcc67936e)
![Screenshot 2025-05-10 162327](https://github.com/user-attachments/assets/c2adf90c-d21f-458a-9875-3db028be1a1a)
