# Customer Shopping Behavior Analysis

An end-to-end **data analytics project** analyzing 3,900 customer purchases to understand shopping patterns, customer segments, product performance, discounts, subscriptions, and revenue.

### Tech Stack

**Python · Pandas · PostgreSQL · SQL · Power BI**

---

## 📊 Dashboard
The Power BI dashboard provides an interactive view of:

- Customer count
- Average purchase amount
- Average review rating
- Subscription distribution
- Revenue and sales by category
- Revenue and sales by age group
- Filters for gender, category, subscription status, and shipping type

---

## 🎯 What This Project Covers

### 1. Data Cleaning & EDA — Python

The dataset was explored and prepared using Python and Pandas.

Key steps included:

- Loading and inspecting the dataset
- Checking missing values and data types
- Imputing missing review ratings using category-level median ratings
- Standardizing column names to `snake_case`
- Creating `age_group`
- Creating `purchase_frequency_days`
- Checking redundant variables and removing `promo_code_used`
- Loading the cleaned data into PostgreSQL

### 2. Business Analysis — SQL

PostgreSQL was used to answer business-focused questions including:

- Revenue by gender
- High-spending customers using discounts
- Top-rated products
- Standard vs. Express shipping spend
- Subscribers vs. non-subscribers
- Products most dependent on discounts
- Customer segmentation
- Top 3 products within each category
- Repeat buyers and subscription behavior
- Revenue by age group

### 3. Visualization — Power BI

The analysis was transformed into an interactive dashboard to make the findings easier to explore and communicate.

---

## 🔍 Key Insights

- **3,900 purchases** were analyzed across **18 columns**.
- Customer segments were classified as **New, Returning, and Loyal**.
- **Loyal customers formed the largest segment**, with 3,116 customers.
- **Young Adults** contributed the highest revenue among the analyzed age groups.
- Express-shipping purchases had a slightly higher average purchase amount than Standard shipping.
- **Hat, Sneakers, Coat, Sweater, and Pants** had the highest discount rates in the analysis.
- **Gloves, Sandals, Boots, Hat, and Skirt** were the five highest-rated products by average rating.

---

## 💼 Business Recommendations

Based on the analysis:

- Increase subscription adoption through exclusive benefits.
- Reward repeat customers to strengthen loyalty.
- Review discount strategies to balance sales and margins.
- Promote highly rated and best-selling products.
- Use customer demographics and purchasing behavior for targeted marketing.

---

## 🧩 Project Workflow

```text
Raw Data
   ↓
Python / Pandas
   ↓
Data Cleaning & Feature Engineering
   ↓
PostgreSQL
   ↓
SQL Business Analysis
   ↓
Power BI Dashboard
   ↓
Business Insights
```
