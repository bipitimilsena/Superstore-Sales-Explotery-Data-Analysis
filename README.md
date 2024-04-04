Superstore Sales Analysis 

Introduction

This project analyzes sales data from a superstore using Python and libraries like Pandas, Matplotlib, and Seaborn. The dataset includes order details such as dates, products, sales, quantity, discounts, and profits.

Files

superstore_sales.ipynb: Jupyter Notebook with Python code for analysis.
superstore_sales.xlsx: Excel file with raw sales data.

Analysis

Data Cleaning and Exploration:

Loaded data into a Pandas DataFrame.
Explored data using head(), tail(), info(), and describe() to understand its structure.
Checked for missing values.
Data Preprocessing:

Converted 'year' column to datetime format.
Created 'month_year' column.
Monthly Sales Analysis:

Grouped data by 'month_year' and calculated total sales.
Plotted monthly sales using Matplotlib and Seaborn.
Product Analysis:

Grouped data by 'product_name' and calculated total sales and quantity sold.
Identified top 10 products.
Plotted top 10 products by sales and quantity using Seaborn.
Category-wise Profit Analysis:

Grouped data by 'category' and calculated total profit.
Plotted total profit by category using Seaborn.
How to Run
Clone repository.
Install Jupyter Notebook and required libraries.
Open superstore_sales.ipynb.
Execute cells sequentially.
Conclusion
This analysis offers insights into superstore sales performance, aiding stakeholders in data-driven decision-making for sales optimization and profit maximization.
