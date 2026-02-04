📊 Customer Shopping Behavior Analysis
Overview

This project focuses on analyzing customer purchasing behavior to uncover trends in spending, product preferences, and customer engagement. The analysis combines Python for data cleaning and exploration, PostgreSQL for structured querying, and Power BI for visualization.

The final insights are summarized in a professional report and an interactive dashboard designed to support data-driven business decisions.

Dataset

The dataset contains 3,900 customer transactions across multiple product categories.

Key data areas include:

Customer demographics (age, gender, location, subscription status)

Purchase details (product, category, price, season, size, color)

Behavioral metrics (discount usage, purchase frequency, review ratings, shipping type)

Some missing values were present in the review rating column and were handled during data cleaning.

Tools & Technologies

Python (Pandas, NumPy, Matplotlib/Seaborn) – Data cleaning and exploratory data analysis (EDA)

PostgreSQL – SQL-based business analysis

Power BI – Interactive dashboard and data visualization

Jupyter Notebook – Python analysis workflow

PDF Report – Final documented findings

Project Workflow
1. Data Preparation (Python)

Loaded and explored the dataset

Handled missing values using appropriate imputation methods

Standardized column names for consistency

Created new features such as age groups and purchase frequency metrics

Validated data consistency and removed redundant columns

2. Database Analysis (PostgreSQL)

Imported the cleaned dataset into PostgreSQL

Wrote SQL queries to analyze:

Revenue patterns across customer groups

High-spending customers and discount behavior

Product performance and ratings

Subscription impact on spending

Customer segmentation and repeat purchase behavior

3. Data Visualization (Power BI)

Built an interactive dashboard to display:

Sales trends and revenue breakdowns

Customer segmentation insights

Product performance comparisons

Shipping and subscription behavior

4. Reporting

Summarized findings, insights, and business recommendations in a structured PDF report

Dashboard Highlights

The Power BI dashboard enables users to:

Explore revenue by customer demographics

Identify top-performing products and categories

Compare subscriber vs non-subscriber spending

Analyze the impact of discounts and shipping methods

Understand customer loyalty and repeat purchase trends

Key Results & Insights

Certain customer segments contribute significantly more to revenue

Subscription customers tend to show stronger purchasing consistency

A small group of products drives a large portion of sales

Discount strategies influence purchase behavior but require balance

Repeat buyers represent a valuable segment for loyalty programs

How to Run This Project
1. Python Analysis

Open the Jupyter Notebook file

Install required libraries:

pip install pandas numpy matplotlib seaborn psycopg2


Run the notebook cells step-by-step for data cleaning and EDA

2. PostgreSQL Queries

Import the cleaned dataset into PostgreSQL

Open the provided SQL file

Run the queries in pgAdmin or any PostgreSQL client

3. Power BI Dashboard

Open the .pbix file in Power BI Desktop

Refresh the dataset connection if needed

4. Final Report

Open the included PDF report for a summary of insights and business recommendations

Project Outcome

This project demonstrates practical skills in:

Data cleaning and preprocessing

SQL-based business analysis

Data visualization and storytelling

Turning raw data into actionable insights

It reflects a complete end-to-end data analytics workflow suitable for real-world business applications.
