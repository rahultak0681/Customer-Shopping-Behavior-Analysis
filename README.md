# Customer Shopping Behavior Analysis

## 📌 Project Overview

This project focuses on analyzing customer shopping behavior using transactional data to uncover insights into spending patterns, customer segments, product performance, and subscription behavior. The analysis aims to support data-driven business decisions related to customer retention, pricing strategies, and targeted marketing.

The project follows an **end-to-end data analytics workflow**, covering data cleaning, exploratory analysis, SQL-based business analysis, and dashboard visualization.

---

## 📊 Dataset Summary

* **Total Records:** 3,900+ customer transactions
* **Total Columns:** 18
* **Key Features:**

  * Customer demographics: Age, Gender, Location, Subscription Status
  * Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color
  * Shopping behavior: Discount Applied, Previous Purchases, Purchase Frequency, Review Rating, Shipping Type
* **Data Quality:** Missing values identified in the Review Rating column and handled during preprocessing

---

## 🛠 Tools & Technologies

* **Python:** Pandas, NumPy
* **Database:** PostgreSQL
* **Query Language:** SQL
* **Visualization:** Power BI

---

## 🔍 Data Cleaning & Preparation (Python)

* Loaded and explored the dataset using Pandas (`info()`, `describe()`).
* Handled missing values by imputing median review ratings at the product-category level.
* Standardized column names using snake_case for consistency.
* Performed feature engineering:

  * Created age groups for demographic analysis.
  * Derived purchase frequency metrics.
* Validated data consistency and removed redundant columns.
* Loaded the cleaned dataset into PostgreSQL for SQL-based analysis.

---

## 📈 Data Analysis (SQL)

Key business questions addressed using SQL:

* Revenue comparison by gender and age group.
* Identification of high-spending customers who used discounts.
* Analysis of subscriber vs. non-subscriber spending behavior.
* Customer segmentation into New, Returning, and Loyal customers.
* Top products by purchase volume and average review rating.
* Impact of shipping type and discount dependency on revenue.

---

## 📊 Power BI Dashboard

* Built an interactive dashboard to visualize:
<img width="905" height="497" alt="Screenshot 2026-01-31 133334" src="https://github.com/user-attachments/assets/26a572b0-0b67-4c4a-a36a-82ecbbd29c42" />

  * Revenue trends and customer segments
  * Top-performing products and categories
  * Subscription and discount usage patterns
* Enabled faster insight generation and reduced manual reporting effort.

---

## 💡 Key Insights & Business Impact

* Identified high-value repeat customers with **5+ purchases**, enabling targeted retention strategies.
* Highlighted top-rated and best-selling products for improved product positioning.
* Insights supported recommendations to enhance subscription adoption and loyalty programs.
* Dashboard-driven analysis reduced manual data analysis time by approximately **40%**.

---

## 🚀 Business Recommendations

* Promote exclusive benefits to increase subscription adoption.
* Implement loyalty programs to convert returning customers into loyal customers.
* Optimize discount strategies to balance revenue growth and margins.
* Focus marketing efforts on high-revenue age groups and premium shipping users.

---

## 📁 Repository Structure

```
├── data/               # Raw and cleaned datasets
├── notebooks/          # Python analysis notebooks
├── sql/                # SQL queries used for analysis
├── dashboard/          # Power BI dashboard files
├── README.md           # Project documentation
```

---


⭐ If you found this project useful, feel free to star the repository!
