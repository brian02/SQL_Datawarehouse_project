# SQL Data Warehouse Project

## 📌 Project Overview

This project demonstrates the design and implementation of a SQL-based Data Warehouse for consolidating, transforming, and analyzing data from multiple sources.

The goal is to build a structured data warehouse that supports efficient data querying, reporting, and analytical decision-making.

## 🏗️ Data Architecture

The project follows a Medallion-style data architecture consisting of three layers:

* **Bronze Layer:** Stores raw data from source systems.
* **Silver Layer:** Cleans, validates, and transforms raw data.
* **Gold Layer:** Contains business-ready data structured for analytical queries and reporting.

## 🎯 Project Objectives

* Design a data warehouse using SQL.
* Integrate data from multiple source systems.
* Develop ETL/ELT processes for data extraction, transformation, and loading.
* Clean and validate data to improve data quality.
* Create fact and dimension tables using a star schema.
* Write SQL queries to support business analysis and reporting.

## 🛠️ Tools & Technologies

* **Database:** [SQL Server / PostgreSQL / MySQL]
* **Language:** SQL
* **Version Control:** Git and GitHub
* **Data Source:** [CSV files / sample databases / other sources]
* **Documentation:** Markdown

## 📂 Repository Structure

```text
sql-data-warehouse/
│
├── datasets/             # Source data files
├── scripts/
│   ├── bronze/           # Raw data ingestion
│   ├── silver/           # Data cleaning and transformation
│   └── gold/             # Analytical models
├── docs/                 # Architecture and data models
├── tests/                # Data quality checks
├── README.md             # Project documentation
└── LICENSE               # Project license (optional)
```

*The folder structure will be updated as the project develops.*

## 🔄 Data Pipeline

1. **Extract:** Obtain data from the source files or systems.
2. **Load:** Import raw data into the Bronze layer.
3. **Transform:** Clean and standardize data in the Silver layer.
4. **Model:** Build fact and dimension tables in the Gold layer.
5. **Analyze:** Use SQL queries to answer business questions and generate insights.

## 📊 Data Modeling

The Gold layer will use a star schema consisting of:

<img width="1125" height="585" alt="data_architecturee" src="https://github.com/user-attachments/assets/20a71cca-b94d-46a0-adb6-5e1be2aeb23c" />



* **Fact Tables:** Store measurable business events, such as sales, transactions, or orders.
* **Dimension Tables:** Store descriptive attributes, such as customers, products, dates, and locations.

## ✅ Key Features

* Layered data architecture
* SQL-based data transformation
* Data quality validation
* Fact and dimension modeling
* Analytical SQL queries
* Reproducible database setup and loading process

## 🚀 Getting Started

1. Clone this repository.
2. Install and configure the required database engine.
3. Download or prepare the source datasets.
4. Execute the SQL scripts in the appropriate order: Bronze, Silver, then Gold.
5. Run the analytical queries to explore the resulting data.

*Detailed setup instructions will be added as the project progresses.*

## 📚 What I Learned

This project is intended to develop practical skills in:

* SQL development and database management
* Data warehouse architecture
* ETL/ELT pipeline design
* Data cleaning and transformation
* Dimensional modeling
* Data quality testing
* Git and GitHub project documentation

## 📌 Project Status

**Status:** In Progress

This repository is being developed as a hands-on data warehousing project to demonstrate SQL development and data engineering fundamentals.

## 👤 Author

**FBrian C.**
