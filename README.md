# Enterprise-Grade Data Warehouse Solution 🏢

## Overview
This project implements a scalable, layered SQL data warehouse architecture designed for structured reporting and data analysis. The warehouse follows the bronze-silver-gold model, ensuring clean, validated, and business-ready data. It includes custom ETL pipelines, data transformation scripts, and robust data quality validation.

## Features 🚀
- Three-tier architecture: Bronze (raw), Silver (cleaned), and Gold (aggregated) layers
- End-to-end ETL pipelines for structured data flow
- Stored procedures for data transformation and loading
- Data quality checks for validation and accuracy
- Optimized schema design for scalable queries
- Power BI integration for business intelligence

## Technologies Used 🛠️
- **SQL (MSSQL)** 🛢️
- **ETL Pipelines** 🔄
- **Python** 🐍
- **Git & GitHub** 🗂️

## Installation & Setup 🏗️
### Clone the Repository
```bash
git clone https://github.com/MothilalShiva/E-Commerce_Analysis_PowerBI.git
cd E-Commerce_Analysis_PowerBI
```

### Set Up Database (MySQL)
```sql
-- Create database and tables
CREATE DATABASE ecommerce_dw;
-- Run schema.sql file inside the repo to generate tables
```

### Load Data
```bash
-- Load CSV files using the provided Python ETL scripts or MySQL Workbench
```

### Run Transformation
```sql
-- Execute stored procedures for data transformation from bronze to silver to gold layers
CALL transform_bronze_to_silver();
CALL transform_silver_to_gold();
```

## Project Structure 📂
```
Enterprise_Data_Warehouse_Solution/
│── scripts/                    # Python ETL and data loading scripts
│── schema/                    # SQL schema and DDL files
│── procedures/                # Stored procedures for data transformation
│── dashboards/                # Power BI dashboard files
│── README.md                  # Project documentation
```

## Results ✅
- Reduced data processing time by 40% through procedural optimization
- Achieved over 95% data accuracy with validation checks
- Delivered business-ready insights using Power BI


