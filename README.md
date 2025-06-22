# Retail-Sales-Analytics
#  Retail Sales Analytics: From Data Cleaning to Insightful SQL Queries

This project demonstrates an end-to-end data analytics workflow using Python and SQL. The dataset `df_orders` was cleaned and prepared using Python (Pandas), and then analyzed using advanced SQL queries to derive key business insights.

---

##  Project Overview

**Objective**: Clean raw sales data and extract business insights such as top-selling products, regional performance, seasonal sales trends, and subcategory growth using SQL.

---

##  Tools & Technologies

- **Python** (Pandas, NumPy)
- **Jupyter Notebook**
- **SQL (T-SQL / MS SQL Server compatible)**
- **Visual Studio Code / SSMS**

---

##  Key Components

### 1. `notebooks/Data_Cleaning.ipynb`

Performed:
- Handling missing values
- Standardizing date formats
- Removing duplicates
- Column renaming
- Data type conversion
- Exporting cleaned dataset to CSV

### 2. `sql/SQL_Data_Analysis.sql`

Contains SQL queries for:
- Top 10 highest revenue-generating products
- Top 5 selling products by region using `ROW_NUMBER()`
- Month-over-month sales comparison (2022 vs 2023)
- Highest sales month per product category
- Subcategory with the highest YoY growth
