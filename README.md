# Customer Churn Analysis

## Project Overview

This project analyzes customer churn patterns to understand customer retention, revenue impact, and customer lifetime value. The analysis uses Python, SQLite, Pandas, NumPy, and data visualization techniques to transform raw customer data into meaningful business insights.

## Business Objective

The objective of this project is to identify customer segments and subscription patterns associated with higher churn and understand their potential impact on business revenue.

The analysis focuses on:

- Customer churn and retention
- Subscription plan performance
- Customer tenure
- Revenue impact
- Average Revenue Per User (ARPU)
- Estimated Customer Lifetime Value (CLTV)
- Customer and regional churn patterns

## Tools & Technologies

- **Python**
- **Pandas**
- **NumPy**
- **SQLite**
- **Matplotlib**
- **Seaborn**
- **Jupyter Notebook**

## Analysis Performed

### 1. Data Cleaning & Preparation
- Cleaned and prepared customer, subscription, and support-related data.
- Handled date fields and prepared variables required for analysis.
- Created analytical features such as customer tenure and churn indicators.

### 2. Churn & Retention Analysis
- Calculated overall customer churn rate and retention rate.
- Compared churn across subscription plans.
- Analyzed churn patterns across different customer segments and states.

### 3. Revenue Analysis
- Calculated Average Revenue Per User (ARPU).
- Analyzed revenue impact associated with customer churn.
- Identified customer groups contributing to potential revenue loss.

### 4. Customer Lifetime Value
- Estimated Customer Lifetime Value (CLTV) using monthly charges and observed customer tenure.
- Compared estimated customer value across different customer segments and subscription plans.

### 5. Data Visualization
Created visualizations using Matplotlib and Seaborn to identify:

- Churn trends
- Retention patterns
- Revenue distribution
- Subscription plan performance
- Customer lifetime value
- Relationships between customer attributes and churn

## Key Insights

- Identified customer segments and subscription plans with higher churn rates.
- Analyzed the relationship between customer tenure, monthly charges, and churn.
- Estimated Customer Lifetime Value (CLTV) to understand differences in customer value.
- Evaluated potential revenue impact associated with customer churn.

## Project Structure

```text
Customer-Churn-Analysis/
│
├── Churn_Analysis.ipynb
├── churn_data.csv
├── .gitignore
└── README.md
