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

sql-data-warehouse-project/
│
├── datasets/                           # Raw ERP and CRM CSV datasets
│
├── docs/                               # Documentation and diagrams
│   ├── etl.drawio                      # ETL flowchart
│   ├── data_architecture.drawio        # Architecture design
│   ├── data_catalog.md                 # Dataset metadata and field descriptions
│   ├── data_flow.drawio                # Data flow diagrams
│   ├── data_models.drawio              # Star schema and modeling diagrams
│   ├── naming-conventions.md           # Table and column naming standards
│
├── scripts/                            # SQL scripts for ETL process
│   ├── bronze/                         # Load raw data
│   ├── silver/                         # Clean and transform data
│   ├── gold/                           # Create analytical data models
│
├── tests/                              # Test queries and validation scripts
│
├── README.md                           # Project overview and documentation (this file)
├── LICENSE                             # License file
├── .gitignore                          # Git ignore settings
└── requirements.txt                    # Project dependencies and setup instructions

---

## 📬 Contact

Feel free to connect with me on [LinkedIn](www.linkedin.com/in/harshitha-challam) or reach out if you have questions about the project.


