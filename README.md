# Customer 360 Sales Performance Dashboard (SQL + Power BI)

Brief Description:
This project analyzes sales performance and customer behavior by building a structured Star Schema model in SQL Server and developing an interactive Power BI dashboard. The goal is to provide a 360-degree view of customers, products, regions, and overall business performance.

## 🛠 Tools Used

SQL Server – Data cleaning, transformation, and star schema modeling

Power BI – Dashboard creation, DAX calculations, and visual analytics

Excel/CSV – Raw dataset (Superstore)

## 🗄 Data Model Used (Star Schema)

Fact Table: fact_sales

Dimension Tables:

dim_customers

dim_products

dim_dates

The model is designed to optimize analytical queries and improve Power BI performance.

## 🔍 Project Overview

Loaded raw Superstore data into SQL Server

Cleaned and prepared the data (type conversion, null handling, standardization)

Created a Star Schema with fact and dimension tables

Built relationships using primary and foreign keys

Imported SQL tables into Power BI for reporting

Created DAX measures for KPIs such as Total Sales, Profit, Margin %, Customer Count, AOV, YTD Sales, and YoY Growth

Designed multiple dashboard pages: Executive Summary, Customer Insights, Product Analysis, and Regional Performance

## 🎯 Key Insights

Identified top-performing regions, products, and customer segments

Analyzed monthly and yearly sales trends

Measured profit margins and discount impact

Highlighted high-value customers and low-margin product categories
