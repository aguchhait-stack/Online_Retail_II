# 📊 Customer Lifecycle Analytics – Online Retail II

## 🔍 Project Overview
This project analyzes transactional e-commerce data to understand customer behavior across the lifecycle—from acquisition to retention and churn.

The dataset contains over 1 million transactions across two years.

---

## 🧩 Architecture (Medallion Design)

### 🥉 Bronze Layer
- retail_raw
- Raw ingested data

### 🥈 Silver Layer
- retail_clean
- retail_returns
- Cleaned and structured data

### 🥇 Gold Layer
- retail_features
- cohort_table
- country_revenue

---

## 🛠️ Tech Stack
- DuckDB (SQL)
- Python (planned)
- Power BI / Tableau (planned)

---

## 🚀 Status
- Data ingestion ✅
- Data cleaning ✅
- Cohort analysis ⬜
- Churn modeling ⬜