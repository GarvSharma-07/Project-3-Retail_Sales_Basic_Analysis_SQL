# Project-3-Retail_Sales_Basic_Analysis_SQL

Exploratory Data Analysis (EDA) project on a retail sales data warehouse using T-SQL (SQL Server). The project analyzes customer, product, and sales fact tables to generate business insights around sales performance, customer behavior, and product trends.

## Dataset
Star-schema data warehouse (`DataWarehouseAnalytics` database) with the following tables:
- `Gold.dim_customers` — customer details (country, gender, birthdate)
- `Gold.dim_products` — product details (category, subcategory, cost)
- `Gold.fact_sales` — sales transactions (order date, quantity, sales amount, price)

## Tools Used
- SQL Server (T-SQL)

## Analysis Performed

**1. Dimensions Exploration**
- Unique customer countries
- Unique product categories, subcategories, and products

**2. Date Exploration**
- First and last order date, total order duration in months
- Youngest and oldest customer by birthdate

**3. Measures Exploration (Key Metrics)**
- Total sales, total items sold, average selling price
- Total number of orders, products, and customers
- Consolidated key metrics report

**4. Magnitude Analysis**
- Total customers by country and gender
- Total products by category
- Average cost and total revenue by category
- Revenue by customer
- Item distribution across countries

**5. Change Over Time Trends**
- Yearly and monthly sales trends with customer counts
- Compared three different SQL approaches: `GROUP BY`, `DATETRUNC()`, and `FORMAT()`

## Key SQL Concepts Used
- Joins (multi-table)
- Aggregate functions (`SUM`, `AVG`, `COUNT`)
- `GROUP BY` and `ORDER BY`
- Subqueries
- Date functions (`DATEDIFF`, `DATETRUNC`, `FORMAT`)
- `DISTINCT`

## File
- `SOLUTION_OF_SQL_DA_PROJECT.sql` — full query file with all analysis questions and solutions
