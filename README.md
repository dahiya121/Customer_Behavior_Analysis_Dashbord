# 🛒 Customer Shopping Behavior Analysis

**A Complete Data Analytics Project using Python, PostgreSQL, and Power BI**

## 📌 Project Overview

This project explores customer shopping patterns using a dataset of **3,900 transactions** across various product categories.
The goal is to uncover insights related to **spending behavior, customer segmentation, subscription trends, product performance, and seasonal preferences**, enabling data-driven business decisions.

The project is structured across **Python (EDA + Cleaning)**, **PostgreSQL (Business Queries)**, and **Power BI (Dashboard Visualization)**.

---

## 📂 Tech Stack

* **Python:** Pandas, NumPy, Matplotlib/Seaborn, SQLAlchemy
* **Database:** PostgreSQL
* **Visualization:** Power BI
* **Other tools:** Jupyter Notebook, DBeaver/pgAdmin
* **Version Control:** Git & GitHub

---

## 📊 Dataset Summary

* **Rows:** 3,900

* **Columns:** 18

* **Key Features:**

  * Customer demographics (Age, Gender, Location, Subscription Status)
  * Purchase details (Item, Category, Amount, Season, Size, Color)
  * Purchase behavior (Discount Applied, Promo Code, Review Rating, Previous Purchases)
  * Shipping Type, Purchase Frequency

* **Missing Data:** 37 missing values in the *Review Rating* column

---

## 🧹 1. Exploratory Data Analysis (Python)

### ✔ Data Cleaning & Preparation

* Loaded dataset using pandas
* Summary analysis using `df.info()` and `df.describe()`
* Handled missing values
  ➤ *Review Rating* imputed using **median rating per product category**
* Column names standardized to **snake_case**
* Feature engineering:

  * `age_group` (binned age ranges)
  * `purchase_frequency_days`
* Removed redundant columns (*promo_code_used*)
* Exported cleaned data to **PostgreSQL** using SQLAlchemy

---

## 🛢 2. SQL Business Analysis (PostgreSQL)

Key business questions answered:

1. **Revenue by Gender**
2. **High-Value Discount Users**
3. **Top 5 Products by Average Rating**
4. **Revenue Comparison by Shipping Type**
5. **Subscribers vs. Non-Subscribers Spending Patterns**
6. **Most Discount-Dependent Products**
7. **Customer Segmentation** (New, Returning, Loyal)
8. **Top 3 Products per Category**
9. **Relationship Between Repeat Buyers & Subscriptions**
10. **Revenue Contribution by Age Group**

All SQL queries used to derive insights are included in the `sql/` folder (if applicable).

---

## 📈 3. Power BI Dashboard

An interactive dashboard was created to visually represent insights:

* Customer segments
* Category performance
* Revenue distribution across demographics
* Shipping type comparison
* Discounts & subscription behavior
* Top-rated and top-selling products

The dashboard helps stakeholders quickly understand customer trends and business opportunities.

---

## 💡 Business Recommendations

Based on the insights:

* **Increase subscription engagement** through exclusive benefits
* **Launch loyalty programs** for high-frequency buyers
* **Optimize discount strategy** to protect margins
* **Highlight best-rated products** in campaigns
* **Target marketing** towards high-revenue age groups and express-shipping users

---

## 📁 Project Structure

```
│── data/
│   └── raw_dataset.csv
│── notebooks/
│   └── customer_sales.ipynb
│── sql/
│   └── customers.sql
│── powerbi/
│   └── customer sales.pbix
│── src/
│   └── db_connection.py
│── README.md
```

---



## 📬 Contact

**Author:** Praveen Dhaiya

**Email:** *dhaiyapraveen4@gmail.com*

**LinkedIn:** *www.linkedin.com/in/praveen-dahiya01*

---

