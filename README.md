# Customer_Shopping_Behavior-Analysis
Data analytics project shocasing customer behavior analysis
customer-behavior-analysis/


│
├── data/


│                └── customer_behavior.csv          # Raw dataset


│
├── python/


│                └── eda_cleaning.ipynb             # Data cleaning and EDA notebook


│
├── sql/


│                 └── business_queries.sql           # PostgreSQL analysis queries


│
├── dashboard/


│               └── customer_behavior.pbix         # Power BI dashboard file


│
├── report/


│               └── project_report.pdf             # Formal project report

Overview
This is a complete end-to-end data analytics project that analyzes retail customer shopping behavior across 3,900 customers and 19 attributes. The project covers the full analytics workflow — from raw data cleaning in Python, to advanced SQL querying in PostgreSQL, to building an interactive Power BI dashboard, and finally to generating a formal stakeholder report and presentation. The goal was to uncover meaningful patterns in customer demographics, purchase habits, subscription behavior, and product preferences that can drive smarter business decisions in retail.

Business Problem
Retail businesses often operate without a clear understanding of who their customers really are and what drives their purchasing decisions. Without this visibility, marketing budgets get wasted on broad campaigns, inventory gets misallocated across product categories, and customer retention suffers due to a lack of personalization. This project addresses that gap by building a data-driven view of customer behavior — answering critical business questions around which demographics spend the most, which categories drive the most revenue, how subscriptions affect purchase frequency, and what shipping preferences reveal about customer expectations.

Project Objective
The objective of this project was to perform a comprehensive analysis of customer shopping behavior data and present the findings in a form that is both analytically rigorous and easily understandable by business stakeholders. The project aimed to identify high-value customer segments, uncover category-level revenue trends, evaluate the impact of discounts and subscriptions on purchasing behavior, and deliver insights through an interactive dashboard and a formal presentation deck.

Dataset Description
The dataset contains 3,900 customer records with 19 attributes covering a wide range of behavioral and demographic variables. The key fields include Customer ID, Age, Gender, Item Purchased, Category (Clothing / Accessories / Footwear / Outerwear), Purchase Amount, Location, Size, Color, Season, Review Rating, Subscription Status, Shipping Type, Discount Applied, Previous Purchases, Payment Method, Frequency of Purchases, Age Group, and Purchase Frequency in Days.
Two additional features were engineered during the data preparation phase — Age Group (Young Adult / Adult / Middle-aged / Senior) and Purchase Frequency Days — to enable more granular demographic and behavioral analysis.

Project Workflow
The project was executed across four structured stages, each building on the output of the previous one.
Stage 1 — Data Cleaning and Exploration (Python)
The raw dataset was loaded into a Pandas DataFrame and thoroughly examined for data quality issues. Missing values were handled using category-based imputation strategies to preserve the statistical integrity of each variable. Outliers were identified and evaluated in the context of their business significance. Feature engineering was performed to create the Age Group and Purchase Frequency Days columns. Exploratory Data Analysis (EDA) was then conducted to understand the distributions of key variables, correlations between demographic attributes and purchase behavior, and patterns in subscription and discount usage. Visualizations were generated using Matplotlib and Seaborn to support the EDA findings.
Stage 2 — Business Analysis (SQL)
The cleaned dataset was connected to a PostgreSQL database to enable structured business querying. Advanced SQL queries were written to calculate total revenue and average purchase amount by product category, measure revenue and sales volume by age group and gender, evaluate discount application rates per product category, segment customers by subscription status and analyze their purchasing frequency, and identify the most preferred shipping types across different demographic segments. These SQL results formed the analytical foundation for the Power BI dashboard.
Stage 3 — Dashboard Creation (Power BI)
An interactive Customer Behavior Dashboard was designed and built in Microsoft Power BI to communicate the SQL findings visually. The dashboard features three KPI cards at the top displaying Number of Customers (3.9K), Average Purchase Amount ($59.76), and Average Review Rating (3.75). A donut chart shows the percentage split of customers by subscription status — 73% non-subscribers versus 27% subscribers. Two bar charts compare Revenue by Category and Sales by Category side by side, allowing quick identification of top-performing product lines. Two horizontal bar charts break down Revenue by Age Group and Sales by Age Group to highlight demographic spending patterns. A dynamic filter panel on the left allows users to slice all visuals simultaneously by Subscription Status, Gender, Category, and Shipping Type.
Stage 4 — Documentation and Reporting
A formal project report was created documenting the end-to-end methodology, findings, and business recommendations. A professional stakeholder presentation deck was generated using Gamma AI, translating the technical analysis into a visually compelling narrative suitable for business audiences.

Key Insights
Clothing is the dominant product category, generating approximately $100K in revenue and leading in sales volume with around 1,600 units sold. Accessories rank second, followed by Footwear and Outerwear. Seventy-three percent of customers have no active subscription, representing a major untapped opportunity for the business to grow recurring revenue through targeted subscription campaigns and loyalty incentives. Young Adults are the highest-spending age group with $62K in revenue and 2.01M in sales volume, making them the most valuable demographic segment. Middle-aged customers follow closely at $59K in revenue and 1.94M in sales. Revenue and sales are distributed fairly evenly across all four age groups — Young Adult, Adult, Middle-aged, and Senior — suggesting the brand has strong cross-demographic appeal with no single age group dominating disproportionately. The average review rating of 3.75 is consistent across categories, indicating stable but improvable customer satisfaction levels across the product range.

Tools and Technologies Used
This project used Python with the Pandas library for data loading, cleaning, and exploratory analysis. Matplotlib and Seaborn were used for EDA visualizations. PostgreSQL was used as the relational database for structured business querying using advanced SQL. Microsoft Power BI was used for dashboard design, DAX measure creation, and interactive reporting. Gamma AI was used to generate the stakeholder presentation deck. Microsoft Excel was used for initial data inspection and formatting.

Skills Demonstrated
This project demonstrates end-to-end data analytics capability including data cleaning and feature engineering in Python, exploratory data analysis and statistical summarization, advanced SQL querying for business intelligence, data modeling and DAX measure creation in Power BI, interactive dashboard design with cross-filtering and slicers, demographic and behavioral customer segmentation, business insight generation and stakeholder communication, and AI-assisted presentation design.

This is how Dashboard look like(https://github.com/abbas620/Customer_Shopping_Behavior-Analysis/blob/main/Customer%20Shopping%20Behavior.png)

