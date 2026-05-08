# Customer Churn Analysis Dashboard

## Project Overview

This project focuses on analyzing customer churn behavior using Power BI and business intelligence techniques. The goal of the project is to identify why customers leave the company and provide actionable business insights to improve customer retention.

The dashboard includes KPI analysis, churn distribution analysis, customer segmentation, contract-based churn analysis, and pricing impact analysis.

---

# Business Problem

Customer churn is one of the major challenges faced by subscription-based businesses. This project helps answer:

- Why are customers leaving?
- Which customers are most likely to churn?
- Which customer segments are most valuable?
- How can retention be improved?

---

# Tools & Technologies Used

- Power BI
- Python
- Pandas
- Jupyter Notebook
- DAX
- Data Visualization

---

# Dataset

Dataset Used:
Telco Customer Churn Dataset

Main columns:
- customerID
- tenure
- MonthlyCharges
- TotalCharges
- Contract
- InternetService
- PaymentMethod
- Churn

---

# Key KPIs

## Churn Rate

Measures the percentage of customers who left the company.

## Retention Rate

Measures the percentage of customers retained.

## Revenue Loss

Revenue lost due to customer churn.

## Total Customers

Total customer count in the dataset.

---

# Dashboard Features

## KPI Cards
- Total Customers
- Churn Rate
- Retention Rate
- Revenue Loss

## Interactive Visualizations
- Customer Churn Distribution
- Contract Type vs Customer Churn
- Customer Segment vs Churn
- Average Monthly Charges by Churn

## Interactive Filters
- Gender
- Contract
- Internet Service
- Payment Method

---

# Deep-Dive Analysis

## Customer Segmentation

Customers were segmented into:
- New Customers
- Regular Customers
- Loyal Customers

based on tenure.

## Contract Analysis

Month-to-month contract customers showed significantly higher churn rates compared to long-term contract users.

## Pricing Analysis

Customers with higher monthly charges demonstrated increased churn probability.

---

# Key Business Insights

- New customers are more likely to churn during the early subscription period.
- Long-term contracts improve customer retention.
- Higher monthly charges may increase customer churn risk.
- Loyal customers contribute stable recurring revenue.

---

# Business Recommendations

- Encourage long-term contracts through discounts and loyalty programs.
- Improve onboarding experience for new customers.
- Introduce personalized retention offers for high-risk customers.
- Review pricing strategies for premium customers.

---

# Dashboard Preview

(Add dashboard screenshot here)

---

# Project Structure

```text
customer-churn-analysis-dashboard/
│
├── data/
├── dashboard/
├── images/
├── notebooks/
├── README.md
└── requirements.txt
```

---

# Future Improvements

- Churn prediction using Machine Learning
- Advanced customer segmentation
- Cohort analysis
- Real-time dashboard integration

---

# Author

Sam
