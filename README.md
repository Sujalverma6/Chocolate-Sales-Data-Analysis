🍫 Chocolate Sales Data Analysis
📌 Project Overview

This project analyzes a transactional chocolate sales dataset to uncover insights into product performance, revenue trends, geographic distribution, and salesperson efficiency.
The analysis focuses on data cleaning, feature engineering, aggregation, and visualization using Python.

🎯 Objectives

Clean and preprocess raw sales data for analysis

Analyze sales performance by product, country, and salesperson

Engineer profitability metrics to evaluate revenue efficiency

Visualize trends and top performers to support business insights

🧰 Tools & Technologies

Python

Pandas – data cleaning, transformation, aggregation

NumPy – numerical operations

Matplotlib & Seaborn – data visualization

Jupyter Notebook

📂 Dataset Description

The dataset contains transactional chocolate sales records with the following key fields:

Sales Person – Name of the salesperson handling the transaction

Product – Chocolate product name

Country – Country where the sale occurred

Date – Transaction date

Amount – Revenue per transaction (originally currency-formatted text)

Boxes Shipped – Number of boxes sold

🧹 Data Cleaning & Preparation

The following preprocessing steps were performed:

Converted revenue values from currency strings to numeric format

Parsed date strings into datetime objects

Extracted month, year, and month name for time-based analysis

Removed invalid or missing values

Validated dataset integrity (no negative or missing revenue)

🧮 Feature Engineering

New features were created to enhance analysis:

Revenue_Per_Box = Amount / Boxes Shipped

Used to measure product-level revenue efficiency

Month, Year, Month_Name

Used for trend and seasonal analysis

Year_Month (Period)

Prepared for potential time-series aggregation

📊 Key Analyses Performed
🔹 Product Analysis

Identified top products by total revenue

Ranked products by average revenue per box to highlight high-margin items

🔹 Country Analysis

Analyzed top countries by total revenue

Compared shipment volume across regions

Visualized monthly revenue trends by country

🔹 Salesperson Performance

Ranked salespersons by total revenue generated

Analyzed sales volume handled by each salesperson

📈 Visualizations

Bar charts for top products and countries by revenue

Horizontal bar plots for revenue-per-box comparison

Monthly revenue trends segmented by country

💡 Key Insights

Certain products generate higher revenue per box, indicating better profitability

A small number of countries contribute a significant share of total revenue

Top-performing salespersons consistently handle higher shipment volumes

🚀 How to Run the Project

Clone the repository

Install required libraries:

pip install pandas numpy matplotlib seaborn


Open the Jupyter notebook:

jupyter notebook chocolate_sales.ipynb
