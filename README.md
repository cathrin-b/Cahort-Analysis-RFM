# Customer Behavior Analysis using Cohort Analysis, RFM & K-Means Clustering

## 📌 Project Overview

This project focuses on analyzing customer purchasing behavior using an Online Retail dataset. The main objective is to understand customer retention, identify valuable customer segments, and group customers based on their purchasing patterns.

The project uses Cohort Analysis, RFM Analysis, and K-Means Clustering to generate meaningful customer insights that can support business decision-making.

## 🎯 Project Objectives

- Analyze customer purchasing behavior.
- Understand customer retention using Cohort Analysis.
- Identify customer value using RFM Analysis.
- Segment customers based on Recency, Frequency, and Monetary value.
- Group similar customers using K-Means Clustering.
- Generate business insights for customer retention and marketing strategies.

## 📂 Dataset Information

**Dataset:** Online Retail Dataset

The dataset contains transactional information from an online retail store.

Main columns:
- InvoiceNo
- StockCode
- Description
- Quantity
- InvoiceDate
- UnitPrice
- CustomerID
- Country

## 🛠️ Technologies & Libraries Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## 🔍 Project Workflow

### 1. Data Cleaning & Preprocessing
- Handled missing values.
- Removed duplicate records.
- Removed invalid transactions.
- Prepared data for analysis.

### 2. Cohort Analysis

Analyzed customer retention based on their first purchase month and tracked their purchasing activity over subsequent months.

### 3. RFM Analysis

Used three important metrics:

- **Recency:** How recently a customer made a purchase.
- **Frequency:** How often a customer made purchases.
- **Monetary:** How much money a customer spent.

Customers were segmented into Gold, Silver, and Bronze categories.

### 4. K-Means Clustering

Applied K-Means, an unsupervised machine learning algorithm, to group customers with similar purchasing behavior.

- Applied data transformation and feature scaling.
- Used the Elbow Method to identify a suitable number of clusters.
- Used Silhouette Score to evaluate clustering quality.

## 📊 Key Insights

- Identified different customer purchasing patterns.
- Analyzed customer retention over time.
- Segmented customers based on RFM metrics.
- Identified high-value, regular, and less-active customer groups through clustering.

## 💡 Business Recommendations

- Provide loyalty rewards to high-value customers.
- Use targeted promotions to encourage repeat purchases.
- Develop re-engagement campaigns for inactive customers.
- Use customer segments to create personalized marketing strategies.

## 📁 Project Structure

```text
Customer-Behavior-Analysis/
│
├── Cohort Analysis.ipynb
├── Online Retail.xlsx
└── README.md
```

## 🚀 Conclusion

This project demonstrates how data analytics and unsupervised machine learning can be used to understand customer behavior, measure retention, and identify meaningful customer segments.

The insights can help businesses improve customer engagement, retention, and marketing strategies.

---

**Tools:** Python | Pandas | NumPy | Matplotlib | Seaborn | Scikit-learn
