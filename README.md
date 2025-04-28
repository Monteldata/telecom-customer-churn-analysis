# Telecom-customer-churn-analysis
 Exploratory data analysis project on telecom customer churn using Python. Includes data cleaning, churn insights, and visualizations using Pandas, Matplotlib, and Seaborn.



## Project Overview
This project uses Python to explore customer churn behavior in a telecom company. The goal is to identify patterns that contribute to customer churn and suggest strategies for improving customer retention.

## Data Cleaning
- Standardized column names for consistency.
- Filled missing service information with 'Not Provided'.
- Imputed missing numeric fields with zeros or medians.
- Filled missing churn-related fields with 'Not Churned'.

## Exploratory Data Analysis (EDA)
- **Q1:** What is the overall churn rate? (Pie Chart)
- **Q2:** What customer types are more likely to churn? (Bar Plot)
- **Q3:** Does customer tenure affect churn? (Histogram)
- **Q4:** Do monthly charges impact churn likelihood? (KDE Plot)

Each visualization was saved as a `.png` file and included in the repository.

## Key Insights
- Customers with month-to-month contracts have the highest churn rate.
- Newer customers (lower tenure) are more likely to churn.
- Higher monthly charges slightly correlate with higher churn.

## Recommendations
- Offer incentives for customers on month-to-month plans to upgrade to longer contracts.
- Improve onboarding experiences for new customers to boost retention.
- Monitor pricing strategies for high-paying customers to reduce churn risk.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---
