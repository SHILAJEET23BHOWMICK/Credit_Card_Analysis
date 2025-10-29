# Credit_Card_Analysis
This project explores credit card transaction data using advanced SQL techniques to uncover insights such as top-spending cities, high-value transactions, card-type performance, and gender-based spending patterns. It demonstrates practical use of CTEs, Window Functions, Aggregations, ROLLUP, and Query Optimization for real-world data analytics.



# Objective
The objective of this project is to analyze credit card transaction data using SQL to derive meaningful business insights.
It focuses on understanding spending patterns, customer behavior, and city/card-type performance while demonstrating advanced SQL techniques such as CTEs, Window Functions, Aggregations, ROLLUP, and Query Optimization.
Through this analysis, the project aims to:
Identify top-performing cities and card types by total spend.
Detect spending trends and anomalies across time and demographics.
Compute key metrics like median spend, contribution ratios, and cumulative milestones.
Showcase efficient query design and data-driven storytelling using SQL alone.

# Key SQL Insights
Top 5 Cities by Spend – Total and percentage contribution of each city.
Highest Spend Month by Card Type – Identified peak spending months using window functions.
Cumulative Spend Milestone – Transactions when each card type reached ₹1,000,000 spend.
Lowest Gold Card Contribution City – Found least contributing city using conditional aggregation.
Outlier Detection – Detected unusually high spends using standard deviation.
City Contribution Optimization – Reduced query time using OVER() instead of multiple scans.
Progressive Subtotals – Used ROLLUP for city, year, and month totals.
Median Spend per City – Calculated median using ranking logic.
Gender-Based Spend Share – Percentage of female spending per expense type.
