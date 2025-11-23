📊 SQL Data Analytics Project

A Complete SQL Warehouse + Analytics Portfolio Project

This project contains a fully structured SQL-based analytics system, including database creation, schema design, data modeling, transformations, dimensional analysis, and advanced analytical SQL queries. It is designed as a complete hands-on project to demonstrate skills in SQL, data warehousing, OLAP-style analytics, and data exploration.


---

📁 Project Structure

sql-data-analytics-project/
│
├── datasets/                     # Raw CSV datasets used for loading
├── docs/                         # Documentation and diagrams
├── scripts/                      # All SQL scripts (ETL + analytics)
│     ├── 00_init_database.sql
│     ├── 01_database_exploration.sql
│     ├── 02_dimensions_exploration.sql
│     ├── 03_date_range_exploration.sql
│     ├── 04_measures_exploration.sql
│     ├── 05_magnitude_analysis.sql
│     ├── 06_ranking_analysis.sql
│     ├── 07_change_over_time_analysis.sql
│     ├── 08_cumulative_analysis.sql
│     ├── 09_performance_analysis.sql
│     ├── 10_data_segmentation.sql
│     ├── 11_part_to_whole_analysis.sql
│     ├── 12_report_customers.sql
│     ├── 13_report_products.sql
│
├── README.md
└── LICENSE


---

🚀 Project Overview

The goal of this project is to build a mini data warehouse and perform end-to-end data analytics using only SQL.
It contains:

⭐ A full database creation & schema setup

⭐ Dimension tables, fact tables, and a gold schema

⭐ Over a dozen analytical SQL modules:

Exploratory queries

Ranking & segmentation

KPIs

Cumulative trends

Time-series analytics

Customer & product reports

Part-to-whole breakdowns


⭐ Clean modular SQL scripts ready for teaching, interviews, or portfolio work



---

🏗 Database Architecture

Database Name

DataWarehouseAnalytics

Schemas Used

gold → Final cleaned analytics-ready tables


Key Objects

Dimension Tables (Customers, Products, Dates)

Fact Tables (Sales, Transactions)

Analytical Query Scripts



---

🧰 Prerequisites

You need:

SQL Server (Recommended)

OR a SQL environment supporting GO, USE, schemas, and T-SQL.


> ⚠ Note:
This project uses T-SQL syntax (GO, USE master;, schemas).
It is not compatible with MySQL.




---

🛠 How to Run the Project

Step 1: Create Database & Schemas

Run:

00_init_database.sql

This will:

Drop existing DataWarehouseAnalytics (⚠ destructive)

Create a new database

Create gold schema

Create all dimension & fact tables



---

Step 2: Run Data Exploration Scripts

Scripts include:

Script	Purpose

01_database_exploration.sql	Inspect database structure
02_dimensions_exploration.sql	Explore dimension tables
03_date_range_exploration.sql	Analyze time ranges
04_measures_exploration.sql	Identify measures (KPIs)



---

Step 3: Advanced Analytics

These scripts contain complete analytics queries:

Script	Analysis Type

05_magnitude_analysis.sql	Total, averages, summaries
06_ranking_analysis.sql	Top-N, bottom-N, dense rank
07_change_over_time_analysis.sql	Month-over-month growth
08_cumulative_analysis.sql	Running totals, rolling sums
09_performance_analysis.sql	KPIs and performance metrics
10_data_segmentation.sql	Bucketization, RFM-style cuts
11_part_to_whole_analysis.sql	Contribution analysis



---

Step 4: Final Reports

12_report_customers.sql

13_report_products.sql


These generate structured business-friendly summary reports.
