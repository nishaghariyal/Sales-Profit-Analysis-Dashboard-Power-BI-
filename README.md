# Project Title
ElectroHub Sales & Profit Analysis Dashboard (Power BI)

# Problem Statement
ElectroHub is a retail company having multiple stores in different areas. The company sells products across categories like Electronics, Clothing, Home Appliances, Accessories, Kitchenware, Bags, and Personal Care.
The goal of this project is to analyze store sales performance and generate insights such as:
-> top/bottom products
-> sales trends over time
-> relationship between sales and profit
-> city-wise sales performance
-> discount impact on revenue

# Dataset Used
Dataset Name: Store+Data.xls
Source: Provided dataset (Excel)

# Data Profiling
Performed profiling to understand:
missing values
incorrect data types
duplicates
outliers in sales/profit
unique values in category, city, product

# Data Cleaning & Transformation (Power Query)
Transformations done:
removed null/blank values
corrected data types (date, numeric fields)
removed duplicates
created calculated columns (if required)
formatted category and city values

# Data Modeling
Created relationships between tables to support analysis
Used star schema modeling for better performance and accuracy.

# KPIs & Measures Created (DAX)
Important measures:
Total Profit
Total Quantity Sold
Sum Of Net Sales

# Dashboard Objectives / Questions Solved
✔ Q1. Top/Bottom 5 products
based on Sales, Profit, Quantity Sold
✔ Q2. Sales Trend Analysis
daily / monthly / quarterly / yearly trend visuals
✔ Q3. Relationship between Sales and Profit
scatter plot / correlation analysis
✔ Q4. Compare Sales/Profit/Quantity between two periods
using slicers and time filter
✔ Q5. Average Discount by Discount Category
discount category wise average discount
✔ Q6. Total number of Orders
order count KPI card
✔ Q7. Detailed Order-level Table
sales, profit, discount, net sales
filter options: product, date, customer id, promotion
✔ Q8. Sales by Cities
city-wise sales analysis using map visual

# Tools Used
Microsoft Power BI
Power Query Editor
DAX Measures
Excel Dataset (storedata.xls)

# Final Outcome
Built an interactive Power BI dashboard that helps ElectroHub to:
-> identify best/worst products
-> track performance over time
-> understand discount impact on profit
-> compare performance across periods
-> analyze city-wise revenue contribution
