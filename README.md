Customer 360 Sales Dashboard (SQL + Power BI)

A data analytics project that builds a Customer 360° view using SQL Server for data modeling and Power BI for dashboarding.
The project provides insights into sales, customers, products, and regional performance.

🛠 Tools Used

SQL Server

Power BI

Excel/CSV (source data)

🗄 Data Model (Star Schema)

Fact Table:

fact_sales

Dimension Tables:

dim_customers

dim_products

dim_dates

🔍 SQL Work Performed

Data cleaning and transformation

Creating dimension & fact tables

Handling duplicates and nulls

Defining primary/foreign keys

Building star schema relationships

📈 Power BI Dashboard Features

Executive Summary: Sales, Profit, Margin, KPIs

Customer Insights: Top customers, segments

Product Analysis: Category & sub-category performance

Regional Performance: Region-wise sales & profit

Sales Trends: MTD, YTD, YoY Growth

🧮 Sample DAX Measures
Total Sales = SUM(fact_sales[Sales])
Total Profit = SUM(fact_sales[Profit])
Profit Margin % = DIVIDE([Total Profit], [Total Sales], 0)
Customer Count = DISTINCTCOUNT(dim_customers[Customer_ID])

🎯 Key Insights

High-performing regions identified

Top product categories driving revenue

Customer segments contributing most sales

Discount impact on profitability
