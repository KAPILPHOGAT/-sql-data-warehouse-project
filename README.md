# -sql-data-warehouse-project
Building a modern data warehouse with SQL Server, including ETL processes ,data modelling, and analytics.
Welcome to the Data Warehouse and Analytics Project repository! ✍
This project demonstrates a comprehensive data warehousing and analytics solution, from building a data warehouse to generating actionable insights. Designed as a portfolio project highlights industry best practices in data engineering and analytics.
 
### Project Requirements

### Building the Data Warehouse (Data Engineering)

### Objective

Develop a modern data warehouse using SQL Server to consolidate sales data, enabling analytical reporting and informed decision-making.

### Specifications
- **Data Sources**: Import data from two source systems (ERP and CRM) provided as CSV files.
- **Data Quality**: Cleanse and resolve data quality issues prior to analysis.
- **Integration**: Combine both sources into a single, user-friendly data model designed for analytical queries.
- **Scope**: Focus on the latest dataset only; historization of data is not required.
- **Documentation**: Provide clear documentation of the data model to support both business stakeholders and analytics teams.



---

### BI: Analytics & Reporting (Data Analytics)

### Objective
Develop SQL-based analytics to deliver detailed insights into:
-**Customer Behavior**
-**Product Performance**
-**Sales Trends**


These insights empower stakeholders with key business metrics, enabling strategic decision-making.


### 📂 Repository Structure


data-warehouse-project/
│
├── datasets/                                   # Raw datasets used for the project (ERP and CRM data)

├── docs/                                     # Project documentation and architecture details


|  ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata



├── scripts/                            # SQL scripts for ETL and transformations

│   ├── bronze/                         # Scripts for extracting and loading raw data

│   ├── silver/                         # Scripts for cleaning and transforming data

│   ├── gold/                           # Scripts for creating analytical models

├── tests/                              # Test scripts and quality files

├── README.md                           # Project overview and instructions

├── LICENSE                             # License information for the repository

---
