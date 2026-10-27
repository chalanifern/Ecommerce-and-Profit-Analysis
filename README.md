# Ecommerce-and-Profit-Analysis
Using python for data analysis to provide visualization insights for Superstore which is an ecommerce.

📊 E-commerce Sales and Profitability Analysis

📌 Project Overview

This project focuses on Exploratory Data Analysis (EDA) of an e-commerce sales dataset to identify business insights related to sales performance, profitability, product categories, customer segments, regional performance, and sales trends over time.

Using Python and data visualization libraries, this project explores historical sales data to understand business performance, identify profitable and loss-making product categories, and investigate monthly sales patterns.

The goal is to transform raw sales data into meaningful insights that can support data-driven business decisions.

🎯 Project Objectives

Analyze overall sales, profit, and profitability.

Identify the best-performing product categories and sub-categories.

Investigate the relationship between discounts and profitability.

Compare sales and profit across geographical regions.

Analyze sales performance across customer segments.

Examine yearly and monthly sales trends.

Calculate month-over-month and year-over-year sales growth.

Identify potential seasonal sales patterns.

📂 Dataset

Dataset: Sample Superstore

The dataset contains approximately 9,994 records and 21 columns covering orders, customers, products, sales, discounts, and profits.

Key Features

Feature

Description

Order ID

Unique identifier for an order

Order Date

Date the order was placed

Ship Date

Date the order was shipped

Ship Mode

Shipping method used

Customer ID

Customer identifier

Segment

Customer segment

Region

Geographical sales region

Category

Main product category

Sub-Category

Product sub-category

Sales

Sales amount

Quantity

Number of items ordered

Discount

Discount applied to an order item

Profit

Profit or loss associated with an order item

The dataset is used for educational and analytical purposes.

🛠️ Technologies and Libraries

The project uses the following technologies:

Python — Data analysis and processing

Pandas — Data manipulation and aggregation

NumPy — Numerical operations

Matplotlib — Data visualization

Seaborn — Statistical data visualization

Google Colab / Jupyter Notebook — Development environment

🔍 Project Workflow

1. Data Loading and Inspection

Loaded the dataset into a Pandas DataFrame.

Examined the dataset's dimensions and column names.

Inspected data types and sample records.

Reviewed missing values and potential duplicate records.

2. Data Cleaning and Preparation

Checked for missing values.

Investigated potential duplicate records.

Converted Order Date and Ship Date into datetime formats.

Extracted year and month information for time-series analysis.

3. Exploratory Data Analysis

Overall Business Performance

Calculated key business metrics, including:

Total Sales

Total Profit

Overall Profit Margin

Number of Unique Orders

Number of Unique Customers

Average Order Value

Product Category Analysis

Compared sales and profit across Furniture, Office Supplies, and Technology to identify the strongest and weakest categories.

Sub-Category Analysis

Investigated individual product sub-categories to identify high-performing products and categories generating losses.

Discount Analysis

Examined average discounts and profit margins across sub-categories to investigate potential relationships between discounting and profitability.

Regional Analysis

Compared sales, profit, order counts, and profit margins across the West, East, Central, and South regions.

Customer Segment Analysis

Analyzed Consumer, Corporate, and Home Office segments to understand their contributions to sales and profitability.

Time-Series Analysis

Investigated sales performance over time, including:

Yearly sales and profit trends

Yearly profit margins

Monthly sales performance

Average monthly sales

Month-over-month sales growth

Year-over-year monthly sales growth

📈 Key Findings

The following findings were identified during the initial analysis.

Overall Performance

Total sales were approximately 2.30 million.

Total profit was approximately 286,409.08.

The overall profit margin was approximately 12.47%.

The dataset contained 5,009 unique orders and 793 unique customers.

Product Category Performance

Technology generated the highest total sales and profit among the three main categories.

Furniture had a relatively low profit margin of approximately 2.49%, despite generating substantial sales.

Office Supplies achieved a profit margin of approximately 17.04%.

Sub-Category Performance

Copiers generated the highest total profit among the sub-categories, at approximately 55,617.82.

Tables generated the largest total loss, at approximately 17,725.48.

Bookcases and Supplies also recorded negative total profits.

Regional Performance

The West region generated the highest total sales and profit.

The West also recorded the highest regional profit margin, at approximately 14.94%.

The Central region had the lowest regional profit margin, at approximately 7.92%.

Customer Segment Performance

Consumer customers generated the highest total sales and profit.

Home Office had the highest profit margin, at approximately 14.05%.

Corporate recorded a profit margin of approximately 13.03%.

Monthly Sales Trends

November had the highest average monthly sales, at approximately 88,115.27.

December and September were the second- and third-highest months by average sales.

February had the lowest average monthly sales, at approximately 14,937.81.

Sales increased from August to September and from October to November in each of the four years analyzed.

January and August experienced substantial year-over-year sales growth in 2017.

These findings highlight areas for further investigation, including low-margin product categories, regional profitability differences, and recurring monthly sales patterns.

Note: These findings are preliminary and should be reconfirmed after resolving the potential duplicate records identified during data inspection.

💡 Business Recommendations

Based on the preliminary findings, the following actions could be investigated:

Review loss-making products: Investigate the costs, pricing, discounts, and sales patterns of Tables, Bookcases, and Supplies.

Evaluate discount strategies: Examine whether discount levels are associated with reduced profitability across products.

Investigate regional performance: Explore the factors contributing to the Central region's comparatively low profit margin.

Optimize inventory planning: Use historical monthly sales patterns to support inventory and promotional planning.

Study customer segments: Investigate how purchasing behavior differs between Consumer, Corporate, and Home Office customers.

Monitor profitability: Track profit margins alongside sales to avoid focusing on revenue growth alone.

These are recommendations for further investigation rather than proven solutions.



📚 Skills Demonstrated

Through this project, I practiced:

Data loading and inspection

Data cleaning and preprocessing

Pandas DataFrame operations

Grouping and aggregation

Feature extraction from datetime columns

Business KPI calculations

Exploratory Data Analysis

Data visualization

Time-series analysis

Interpreting data and communicating business insights

🔮 Future Improvements

Potential extensions include:

Developing an interactive dashboard using Power BI, Tableau, or Streamlit.

Investigating product-level and customer-level profitability in greater detail.

Analyzing shipping delays and their relationship with business performance.

Examining the relationship between discounts, sales, and profit at the transaction level.

Developing sales forecasting models using historical data.

Investigating seasonal patterns with additional statistical methods.

👩‍💻 Author

Chalani Fernando

BSc (Hons) Computer Science

This project was developed as part of my learning journey in Python, data analysis, and exploratory data analysis.

⭐ If you find this project useful, feel free to explore the repository and share feedback.
