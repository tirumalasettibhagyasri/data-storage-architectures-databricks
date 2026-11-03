# Data Storage Architectures & Databricks

## Project Overview
This repository contains my learning and understanding of modern data storage architectures as part of the Data Engineering assignment at Innomatics Research Labs.

The project explores how organizations store, process, manage, and analyze data using different architectures and Databricks.

## Topics Covered

### 1. Data Warehouse
- Stores structured and processed data.
- Supports business intelligence and reporting.
- Uses predefined schemas.

### 2. Data Lake
- Stores structured, semi-structured, and unstructured data.
- Supports large-scale data storage.
- Allows flexible data processing.

### 3. Data Lakehouse
- Combines features of Data Lakes and Data Warehouses.
- Supports reliable data processing and analytics.
- Uses Delta Lake features such as ACID transactions.

### 4. Databricks and Unity Catalog
- Understanding the Databricks Lakehouse Platform.
- Learning the Unity Catalog hierarchy:
  Catalog → Schema → Table.
- Understanding Volumes and Tables.
- Exploring managed and external tables.

### 5. Medallion Architecture
- **Bronze Layer:** Stores raw data.
- **Silver Layer:** Stores cleaned and validated data.
- **Gold Layer:** Stores business-ready data for analytics.

## Architecture Flow

Source Data → Bronze Layer → Silver Layer → Gold Layer → Business Analytics

## Key Learnings
- Differences between Data Warehouse, Data Lake, and Lakehouse.
- Importance of Delta Lake and data reliability.
- Role of Unity Catalog in data governance.
- Difference between Volumes and Tables.
- How Medallion Architecture organizes data processing.

## Published Article

Read my complete technical article on LinkedIn:

[From Raw Data to Business Insights: Understanding Data Warehouse, Data Lake, Lakehouse and Databricks](https://lnkd.in/p/ep484A-p)

## References
- [Databricks Documentation](https://docs.databricks.com/)
- [Microsoft Learn](https://learn.microsoft.com/)

## Author
Tirumalasetti Bhagya Sri

Data Engineering Learner | Innomatics Research Labs
