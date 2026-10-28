Customer Behavior Analysis — Task 1
1. Project Overview

This project analyzes e-commerce customer transactions to understand customer purchasing behavior, identify customer segments, analyze sales trends, and examine churn patterns.

Organization: Alfido Tech
Project: Data Analytics Internship — Task 1

2. Objectives
Clean and prepare customer transaction data.
Perform feature engineering.
Segment customers using Recency, Frequency, and Monetary (RFM) analysis.
Visualize monthly purchase trends and product category sales.
Analyze customer churn indicators.
Provide actionable business recommendations to improve customer engagement.
3. Dataset

Source: Customer Behavior Analysis — Kaggle

The analysis uses the ecommerce_customer_data_large.csv dataset.

The original dataset contains 250,000 records and 13 columns before cleaning.

4. Tools and Technologies
Python
Pandas
NumPy
Matplotlib
Seaborn
Kaggle Notebooks
GitHub
5. Data Cleaning and Feature Engineering

The project includes:

Checking missing values and duplicate records.
Converting purchase dates into datetime format.
Creating purchase month and weekday features.
Grouping customers by age where applicable.
Preparing customer-level metrics for RFM analysis.

Missing return values are not automatically assumed to mean that no return occurred.

6. Exploratory Data Analysis
Monthly Purchase Trends

August 2020 recorded a total purchase amount of 16,190,648, the highest among the five leading months identified in the analysis.

Product Category Analysis

The Home category recorded the highest total purchase amount at 171,138,916.

Other category totals:

Clothing: 170,716,122
Electronics: 170,146,025
Books: 169,345,236
Churn Analysis

The dataset contains:

Non-churn records: 199,870
Churn records: 50,130
Record-level churn rate: approximately 20.05%

This is a transaction-record-level figure and should not be interpreted as the unique-customer churn rate.

7. RFM Customer Segmentation

Customers were classified into five segments based on recency, frequency, and monetary value.

Customer Segment	Customers	Average Spending
Regular Customers	17,566	13,607.99
Loyal / Active	10,592	20,083.87
Inactive / At-Risk	10,931	7,400.32
Recent / New	5,373	8,853.82
At-Risk High-Value	5,199	19,449.04

The segment counts and spending values are based on the implemented RFM rules.

8. Business Recommendations for Alfido Tech
Reward loyal customers: Introduce loyalty points, exclusive offers, and repeat-purchase rewards.
Re-engage high-value customers: Send personalized win-back offers to customers with long purchase gaps.
Encourage new customers: Offer relevant product recommendations and second-purchase incentives.
Improve category marketing: Develop targeted campaigns based on observed product category performance.
Monitor retention: Track customer-level churn, repeat-purchase rates, and monthly segment changes.
9. Conclusion

RFM segmentation and transaction analysis provide useful insights into customer purchasing behavior and potential retention opportunities. The findings can help Alfido Tech develop more targeted customer engagement and marketing strategies.

10. Project Files
Task1_Customer_Behavior_Analysis.ipynb — Python analysis notebook.
Supporting visualizations and analysis outputs, where uploaded.
11. Author

GitHub: Ramani537

Project Repository: Task1_Customer_Behavior_Analysis
