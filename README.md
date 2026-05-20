# 📊 Customer Segmentation with RFM & K-Means


## 📖 Introduction & Data Dictionary

RFM + K-Means customer segmentation using the **Online Retail II** dataset (UCI ML Repository). The dataset captures 1,067,371 e-commerce transactions over two years (Dec 2009 - Dec 2011) for a UK-based online retailer.

| Feature | Type | Description |
| :--- | :--- | :--- |
| `InvoiceNo` | Nominal | 6-digit transaction ID. 'C' prefix = cancellation |
| `StockCode` | Nominal | 5-digit product ID |
| `Description` | Nominal | Product name |
| `Quantity` | Numeric | Units purchased per transaction |
| `InvoiceDate` | Numeric | Transaction timestamp |
| `UnitPrice` | Numeric | Price per unit (£) |
| `CustomerID` | Nominal | 5-digit customer ID |
| `Country` | Nominal | Customer country |

**Goal:** Segment customers for targeted CRM strategies.

## 🔍 Project Overview

This project implements data-driven customer segmentation using **RFM (Recency, Frequency, Monetary)** analysis and **K-Means clustering** to transition from generic to targeted CRM strategies.

## 🛠️ Tech Stack

- Python 3.13.5
- pandas 3.0.1
- numpy 2.3.1
- scikit-learn 1.8.0
- matplotlib 3.10.8
- seaborn 0.13.2

## 📥 Setup Instructions

1. Download the dataset from [UCI Online Retail II](https://archive.ics.uci.edu/ml/datasets/Online+Retail+II)
2. Create a folder named `data` in the project root
3. Place `online+retail+ii.zip` inside the `data` folder
4. Run the notebook

## 📄 License & Citation

**Dataset Citation:**  
Chen, Daqing. 2012. Online Retail II. UCI Machine Learning Repository. https://doi.org/10.24432/C5CG6D.

**Dataset License:** Creative Commons Attribution 4.0 International (CC BY 4.0)
