# customer_behavior_analysis
Data analysis project showcasing customer behavior analysis using python, sql and power Bi.

Overview

This project analyzes customer shopping behavior to uncover key insights into sales patterns, customer preferences, and product performance. By leveraging a combination of Python for data processing, PostgreSQL for in-depth querying, and Power BI for interactive visualization, this analysis provides a comprehensive view of retail dynamics. The final findings are summarized in a professional report and presentation.

Dataset

The analysis is based on the customer_shopping_behavior.csv dataset, which includes the following key customer and transaction details:
Customer Demographics: Age, Gender, Location
Purchase Details: Item Purchased, Category, Purchase Amount (USD), Size, Color, Season
Customer Status: Subscription Status, Previous Purchases, Frequency of Purchases
Transaction Info: Shipping Type, Discount Applied, Promo Code Used, Payment Method, Review Rating

Tools Used

Python (Pandas): For initial data loading, exploratory data analysis (EDA), and cleaning.
PostgreSQL: For storing the cleaned data and running complex SQL queries to derive business insights.
Power BI: For creating an interactive dashboard to visualize key metrics and trends.
Gamma: For generating a professional presentation of the project's findings.

Project Steps

Data Loading & Cleaning (Python):

Loaded the raw CSV data into a Pandas DataFrame.
Performed EDA to understand data distribution and identify missing or inconsistent values.
Cleaned the dataset to ensure accuracy for analysis.

Database Management (PostgreSQL):

Set up a PostgreSQL database and imported the cleaned data.
Executed SQL queries to answer specific business questions, such as:
Total revenue by gender.
Top-rated products.
Impact of shipping type on purchase amount.
Spending habits of subscribed vs. non-subscribed customers.
Customer segmentation based on purchase history.

Dashboard Creation (Power BI):

Designed an interactive dashboard to visualize the insights from the SQL analysis.
Key visuals include sales by category, customer demographics, and purchase frequency trends.

Reporting & Presentation:

Compiled key findings into a comprehensive report.
Created a visually appealing presentation using Gamma to communicate insights effectively.

Dashboard

The Power BI dashboard provides an interactive view of the analysis, featuring:
Key Performance Indicators (KPIs): Total Revenue, Average Order Value, Total Customers.
Sales breakdown by category, season, and location.
Customer insights based on demographics and subscription status.
(Note: Open the customer_behavior_dashboard.pbix file in Power BI Desktop to interact with the dashboard.)

Key Results

Identified high-value customer segments based on purchase frequency and total spend.
Uncovered seasonal trends in product category sales.
Determined the impact of discounts and promo codes on average transaction value.
Highlighted top-performing products based on customer review ratings.

How to Run

Data Prep: Run the Python script (not included in this repo, but assumed to be part of your workflow) to clean customer_shopping_behavior.csv.
Database Setup: Create a PostgreSQL database and table, then import the cleaned CSV data.
SQL Analysis: Execute the queries in customer_behavior_sql_queries.sql using your preferred SQL client (e.g., pgAdmin, DBeaver) connected to your PostgreSQL database.
Dashboard: Open customer_behavior_dashboard.pbix with Power BI Desktop. You may need to update the data source settings to point to your local PostgreSQL instance.
