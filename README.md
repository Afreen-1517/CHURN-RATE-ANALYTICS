# 📊 Customer Churn Analysis & Retention Strategy

## 🔍 Project Overview
This project analyzes customer churn behavior using Python, SQL, Excel, and Tableau. The goal is to identify high-risk customers, understand churn patterns, and estimate business impact to support data-driven decision-making.

---

## 🛠️ Tools & Technologies
- Python (Pandas, NumPy, Seaborn, Matplotlib)
- SQL (SQLite)
- Excel (Pivot Tables)
- Tableau (Dashboard)

---

## 📊 Key Analysis Performed

### 🔹 Data Cleaning & Preprocessing
- Handled missing values and ensured data consistency
- Converted data types and created new feature `AvgCharge`

### 🔹 Exploratory Data Analysis (EDA)
- Analyzed churn distribution
- Compared churn vs Monthly Charges
- Identified patterns in customer behavior

### 🔹 SQL Analysis
- Calculated churn rate
- Segmented customers by contract type and tenure
- Identified high-risk customer segments
- Estimated revenue loss due to churn

### 🔹 Customer Segmentation
- Classified customers into:
  - New (<12 months)
  - Mid (12–24 months)
  - Loyal (>24 months)

---

## 📈 Business Impact Analysis

- Identified **723 high-risk customers**
- Estimated **₹69K monthly revenue at risk**
- Simulated retention strategy showing potential recovery of **~₹7K/month**
- Highlighted that **low tenure + high charges → high churn risk**

---

## 📊 Dashboard
- Built interactive dashboard in Tableau
- Visualized churn trends by:
  - Contract type
  - Tenure
  - Payment method
- Added insights for business decision-making

---

## 📌 Key Insights

- Month-to-month contracts show higher churn
- Customers with high monthly charges are more likely to churn
- New customers have higher churn probability
- Retention strategies should target high-risk segments

---

## 📁 Files Included
- `churn_analysis.ipynb` → Python + SQL analysis
- `final_churn_data.csv` → Cleaned dataset
- `queries.sql` → SQL queries
- `dashboard.png` → Tableau dashboard

---

## 🚀 Conclusion
This project demonstrates end-to-end data analysis from data cleaning to business impact estimation, helping organizations reduce churn and improve customer retention strategies.
