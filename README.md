📊 Procurement Spend Analysis (SQL + Power BI)
📌 Project Overview

This project focuses on analyzing procurement spend data using MySQL for data extraction and Power BI for interactive visualization.
The goal is to understand spend patterns by supplier, item category, and time, and to identify top suppliers and monthly trends for better procurement decision-making.

🗂️ Project Files
📁 Procurement-Spend-Analysis
│
├── SQL TASK.sql
├── procurement_data_analysis.pbix
└── README.md

🛠️ Tools & Technologies

Database: MySQL

BI Tool: Power BI Desktop

Query Language: SQL

Modeling: Star Schema

Visualization: Bar charts, Line charts, KPI cards, Slicers

🧾 SQL FILE DESCRIPTION
📄 SQL TASK.sql

This file contains data extraction and aggregation queries written in MySQL to support procurement analysis.

Key Features:

Joins procurement fact and dimension tables (supplier, item, date)

Aggregates total spend by:

Supplier

Item category

Month / Year

Uses:

JOIN

GROUP BY

SUM(), COUNT()

Date-based filtering

Purpose:

The SQL queries generate clean, analysis-ready datasets that are imported into Power BI for visualization.

📊 POWER BI FILE DESCRIPTION
📄 procurement_data_analysis.pbix

This Power BI report provides an interactive procurement spend dashboard built on top of the MySQL data.

Dashboard Highlights:

Spend by Supplier (Bar Chart)

Monthly Spend Trend (Line Chart)

Spend by Item Category (Column Chart)

Top Suppliers by Spend

KPI Cards:

Total Spend

Total Transactions

Average Spend

Interactivity:

Slicers for:

Time Period (Year / Month)

Supplier Rating

Cross-filtering enabled across all visuals

Data Model:

Star schema with:

Fact table: Procurement transactions

Dimension tables: Supplier, Item, Date

DAX measures for dynamic calculations

📈 Business Insights Enabled

Identify top-spending suppliers

Track monthly procurement trends

Analyze category-wise expenditure

Evaluate suppliers based on rating and spend

🚀 How to Use This Project
Step 1: SQL

Open SQL TASK.sql in MySQL Workbench

Execute queries on the procurement database

Ensure tables are populated correctly

Step 2: Power BI

Open procurement_data_analysis.pbix in Power BI Desktop

Update MySQL connection credentials if required

Refresh data

Interact with slicers and visuals

📌 Key Skills Demonstrated

SQL data extraction & aggregation

Relational data modeling

Power BI data modeling (Star Schema)

DAX measures

Dashboard design & storytelling

Naga Srinu
Aspiring Data Analyst | SQL | Power BI | Python
