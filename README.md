# SQL Data Warehouse Project

**Building a modern data warehouse with SQL Server, including ETL processes, data modeling, and analytics.**

Welcome to my **SQL Data Warehouse and Analytics Project** repository! 🚀  
This project is part of my portfolio and showcases my skills in designing, building, and analyzing a data warehouse using SQL Server. It demonstrates real-world practices in data engineering, ETL development, and analytics.

---

## 🏗️ Data Architecture

The project follows the **Medallion Architecture** with three data layers:

![Data Architecture]("C:\Users\Rakesh\Downloads\data_architecture.png")

1. **Bronze Layer**: Ingests raw data from source systems (CSV files) into SQL Server.
2. **Silver Layer**: Cleanses, transforms, and standardizes data for analytical use.
3. **Gold Layer**: Contains business-ready, star-schema-modeled data optimized for analytics and reporting.

---

## 📖 Project Overview

This project includes:

1. **Data Architecture**: Medallion-based multi-layered architecture.
2. **ETL Pipelines**: End-to-end SQL scripts to extract, transform, and load data.
3. **Data Modeling**: Dimensional modeling using star schema.
4. **Analytics & Reporting**: Insights generation through SQL-based analysis.

🎯 **Skills Demonstrated**:
- SQL Development
- ETL Pipeline Development
- Data Modeling
- Data Engineering
- Analytics & Business Intelligence

---

## 🛠️ Tools & Resources

All tools and datasets used in this project are freely available:

- **[Datasets](datasets/)**: CSV files from ERP and CRM systems
- **[SQL Server Express](https://www.microsoft.com/en-us/sql-server/sql-server-downloads)**: Lightweight SQL Server edition
- **[SQL Server Management Studio (SSMS)](https://learn.microsoft.com/en-us/sql/ssms/download-sql-server-management-studio-ssms?view=sql-server-ver16)**: GUI for SQL Server

---

## 🚀 Project Requirements

### Phase 1: Data Engineering

**Objective**: Build a data warehouse that consolidates and cleans sales data from two source systems.

**Steps**:
- Import ERP and CRM data from CSV files
- Clean and standardize data
- Merge sources into a unified data model
- Apply consistent naming conventions
- Document model clearly for business and technical users

---

### Phase 2: Analytics & Reporting

**Objective**: Generate SQL-based business insights, including:

- **Customer Behavior**
- **Product Performance**
- **Sales Trends**

📄 For full details, refer to [docs/requirements.md](docs/requirements.md)

---

## 📂 Repository Structure

data-warehouse-project/
│
├── datasets/                           # Raw datasets used for the project (ERP and CRM data)
│
├── docs/                               # Project documentation and architecture details
│   ├── etl.drawio                      # Draw.io file shows all different techniquies and methods of ETL
│   ├── data_architecture.drawio        # Draw.io file shows the project's architecture
│   ├── data_catalog.md                 # Catalog of datasets, including field descriptions and metadata
│   ├── data_flow.drawio                # Draw.io file for the data flow diagram
│   ├── data_models.drawio              # Draw.io file for data models (star schema)
│   ├── naming-conventions.md           # Consistent naming guidelines for tables, columns, and files
│
├── scripts/                            # SQL scripts for ETL and transformations
│   ├── bronze/                         # Scripts for extracting and loading raw data
│   ├── silver/                         # Scripts for cleaning and transforming data
│   ├── gold/                           # Scripts for creating analytical models
│
├── tests/                              # Test scripts and quality files
│
├── README.md                           # Project overview and instructions
├── .gitignore                          # Files and directories to be ignored by Git
└── requirements.txt                    # Dependencies and requirements for the project
---

## 📬 Contact

Feel free to connect with me on [LinkedIn](www.linkedin.com/in/harshitha-challam) or reach out if you have questions about the project.


