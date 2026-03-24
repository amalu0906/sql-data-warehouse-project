## Data Warehouse and Analytics Project
This repository walks through a complete data warehousing and analytics pipeline ,from the ground up. It is built as a portfolio project to demonstrate real-world data engineering standards and practices.

---

## Data Architecture
The data architecture behind this project is built on the Medallion framework, which structures data into three clearly defined layers - Bronze, Silver and Gold,progressively refining raw inputs into analytics-ready outputs. Below is an architecture diagram depicting the same:

![architecture](https://github.com/user-attachments/assets/d452b4c8-aa46-47b1-b15f-db089e60ffaa)

**Bronze Layer**: Serves as the raw data landing zone, ingesting source data as-is from CSV files directly into the SQL Server Database,preserving it in its original form without any transformation.

**Silver Layer**: Acts as the refinement stage, where raw data undergoes cleansing, standardization and normalization to ensure consistency and accuracy in preparation for analysis.

**Gold Layer**: Delivers business-ready data modeled into a star schema, purpose-built for reporting and analytics consumption.

---

## Project Overview

This project involves: 

**Data Architecture**: Designing a modern data warehouse built on the Medallion Architecture, structuring data across Bronze, Silver, and Gold layers for scalability and clarity.

**ETL Pipelines**: Building robust pipelines that extract data from source systems, apply meaningful transformations, and load it seamlessly into the warehouse.

**Data Modeling**: Developing well-structured fact and dimension tables, carefully optimized to support fast and efficient analytical queries.

**Analytics & Reporting**: Crafting SQL-based reports and dashboards that surface key metrics and translate raw data into actionable business insights.
