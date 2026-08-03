# 🛍️ Customer Shopping Behavior Analysis

An end-to-end Data Analytics project that analyzes customer shopping behavior using **Python, PostgreSQL, and Power BI** to uncover purchasing trends, customer segments, and revenue-driving factors. The project demonstrates the complete analytics lifecycle—from data cleaning and transformation to SQL-based business analysis and interactive dashboard creation.

---

## 📌 Business Problem

A retail company wants to better understand customer shopping behavior to improve:

- Customer engagement
- Product strategy
- Marketing effectiveness
- Customer loyalty
- Revenue growth

The objective is to analyze customer purchase data and identify the factors influencing customer decisions, repeat purchases, and spending patterns. :contentReference[oaicite:0]{index=0}

---

## 📊 Project Overview

This project analyzes **3,900 customer purchase records** across multiple product categories to answer real-world business questions related to:

- Customer demographics
- Shopping behavior
- Product preferences
- Subscription patterns
- Revenue generation
- Discounts and promotions
- Customer loyalty

The project combines:

- **Python** for data cleaning & feature engineering
- **PostgreSQL** for business analytics
- **Power BI** for dashboard development

:contentReference[oaicite:1]{index=1}

---

# 🛠 Tech Stack

| Technology   | Purpose                             |
| ------------ | ----------------------------------- |
| Python       | Data Cleaning & Feature Engineering |
| Pandas       | Data Manipulation                   |
| NumPy        | Numerical Operations                |
| PostgreSQL   | SQL Analysis                        |
| Power BI     | Dashboard & Visualization           |
| SQL          | Business Analytics                  |
| Git & GitHub | Version Control                     |

---

# 📂 Project Structure

```
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── python/
│   ├── data_manipulation.ipynb
│
├── sql/
│   ├── business_analysis.sql
│
├── powerbi/
│   └── Customer_Shopping_Dashboard.pbix
│
├── images/
│   └── dashboard.png
│
├── README.md
└── requirements.txt
```

---

# 📈 Dataset

### Dataset Summary

- **Rows:** 3,900
- **Columns:** 18

### Features

- Age
- Gender
- Location
- Subscription Status
- Item Purchased
- Category
- Purchase Amount
- Season
- Color
- Size
- Discount Applied
- Previous Purchases
- Review Rating
- Shipping Type
- Purchase Frequency

The dataset contained **37 missing values** in the Review Rating column, which were imputed during preprocessing. :contentReference[oaicite:2]{index=2}

---

# 🧹 Data Preparation (Python)

The dataset was cleaned and transformed using Python.

### Data Cleaning

- Imported dataset using Pandas
- Checked schema and descriptive statistics
- Handled missing values
- Standardized column names
- Removed redundant columns
- Loaded cleaned dataset into PostgreSQL

### Feature Engineering

Created additional business features such as:

- Age Group
- Purchase Frequency (Days)

---

# 🗄 SQL Business Analysis

The cleaned data was loaded into PostgreSQL where business questions were answered using SQL.

### Key Analyses

- Revenue by Gender
- High-Spending Discount Users
- Top Rated Products
- Shipping Type Comparison
- Subscriber vs Non-Subscriber Spending
- Discount Dependency by Product
- Customer Segmentation
- Top Products by Category
- Repeat Buyers vs Subscription
- Revenue Contribution by Age Group

These analyses simulate real-world retail reporting and business intelligence use cases. :contentReference[oaicite:3]{index=3}

---

# 📊 Power BI Dashboard

An interactive dashboard was developed to visualize:

- Revenue Analysis
- Customer Demographics
- Purchase Trends
- Product Performance
- Subscription Insights
- Customer Segments
- Shipping Preferences
- Discount Analysis

---

# 💡 Business Insights

The analysis revealed several actionable insights:

- Subscribers generate higher overall revenue.
- Loyal customers contribute significantly to repeat sales.
- Certain products rely heavily on discounts for purchases.
- Customer spending varies across age groups.
- Express shipping customers generally have higher purchase values.
- Highly rated products are strong candidates for promotional campaigns.

---

# 📢 Business Recommendations

Based on the analysis:

- Introduce stronger customer loyalty programs.
- Increase subscriber-exclusive benefits.
- Optimize discount strategies to protect profit margins.
- Promote top-rated products through targeted campaigns.
- Focus marketing efforts on high-value customer segments.
- Personalize offers based on purchase history and demographics.

:contentReference[oaicite:4]{index=4}

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- SQL Query Optimization
- Business Analytics
- Data Visualization
- Dashboard Design
- Customer Segmentation
- Data Storytelling

---

# 📷 Dashboard Preview

> *(Add your Power BI dashboard screenshot here)*

```
images/Customer Shopping Behavior Analysis Dashboard.png
```

---

# 📌 Future Improvements

- Build predictive models for customer churn.
- Implement product recommendation system.
- Forecast future sales using time-series models.
- Deploy dashboard using Power BI Service.
- Automate the ETL pipeline.

---
