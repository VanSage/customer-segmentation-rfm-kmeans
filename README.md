# 📊 Customer Segmentation using RFM Analysis & K-Means Clustering
 
> Transforming retail transaction data into actionable customer insights through data analytics and machine learning.

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-KMeans-orange)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

---

# 📌 Project Overview

Customer segmentation enables businesses to better understand customer purchasing behavior and create personalized marketing strategies.

In this project, I analyzed the **Online Retail Dataset** containing over **541,000 retail transactions** and applied **RFM (Recency, Frequency, Monetary) Analysis** along with **K-Means Clustering** to classify customers into meaningful business segments.

The project demonstrates how data analytics and machine learning techniques can support data-driven decision-making in retail businesses.

---

# 🎯 Business Problem

Retail businesses often have thousands of customers with different purchasing behaviors.

Treating every customer the same leads to:

- Low customer retention
- Inefficient marketing campaigns
- Poor resource allocation
- Reduced profitability

This project addresses these challenges by identifying customer groups based on their purchasing patterns.

---

# 📂 Dataset Information

- **Dataset:** Online Retail
- **Total Transactions:** 541,910
- **Features:** 8
- **Domain:** E-Commerce / Retail Analytics

### Dataset Features

| Feature | Description |
|----------|-------------|
| InvoiceNo | Invoice Number |
| StockCode | Product Code |
| Description | Product Description |
| Quantity | Purchased Quantity |
| InvoiceDate | Purchase Date |
| UnitPrice | Product Price |
| CustomerID | Customer Identifier |
| Country | Customer Country |

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

# 📈 Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Feature Engineering
        │
        ▼
RFM Analysis
        │
        ▼
Feature Scaling
        │
        ▼
Elbow Method
        │
        ▼
K-Means Clustering
        │
        ▼
Customer Segmentation
        │
        ▼
Business Insights
```

---

# 🔍 Data Cleaning

The following preprocessing steps were performed:

- Removed missing Customer IDs
- Removed cancelled invoices
- Removed invalid quantities
- Removed invalid prices
- Converted InvoiceDate to datetime
- Created Revenue feature

---

# 📊 Exploratory Data Analysis

The analysis includes:

- Customer Purchase Distribution
- Revenue Distribution
- Recency Distribution
- Frequency Distribution
- Monetary Distribution
- Correlation Heatmap

---

# 🤖 Machine Learning

The optimal number of clusters was determined using the **Elbow Method**.

A **K-Means Clustering** model was then trained to identify customer segments based on RFM metrics.

---

# 👥 Customer Segments

| Segment | Description |
|----------|-------------|
| ⭐ High Value Customers | High spending, frequent purchases, recent activity |
| 💎 Loyal Customers | Consistent purchasing behavior |
| 🛍️ Regular Customers | Moderate purchase frequency and spending |
| ⚠️ At-Risk Customers | Inactive customers requiring re-engagement |

---

# 💡 Key Business Insights

- High Value Customers contribute the highest revenue.
- Loyal Customers represent a stable revenue source.
- Regular Customers have strong growth potential.
- At-Risk Customers require retention campaigns.
- RFM analysis enables targeted and personalized marketing strategies.

---

# 🚀 Business Recommendations

- Implement loyalty programs for High Value Customers.
- Reward Loyal Customers with exclusive benefits.
- Encourage Regular Customers through personalized offers.
- Launch win-back campaigns for At-Risk Customers.
- Continuously update customer segmentation to adapt to changing purchasing behavior.

---

# 📷 Project Screenshots

> Add screenshots of your notebook and visualizations here.

Examples:

- Dataset Overview
- Elbow Method
- Customer Segment Distribution
- Monetary Analysis
- Correlation Heatmap

---

# 📈 Future Improvements

- Customer Lifetime Value (CLV) Prediction
- Churn Prediction
- Interactive Power BI Dashboard
- Automated Customer Segmentation Pipeline
- Real-time Customer Analytics

---

# 📚 Learning Outcomes

Through this project, I gained practical experience in:

- Data Cleaning
- Exploratory Data Analysis
- Feature Engineering
- RFM Analysis
- Unsupervised Machine Learning
- Customer Analytics
- Business Intelligence
- Data Visualization

---

# 👩‍💻 Author

**Vanshika**

Aspiring Data Analyst

If you found this project helpful, consider giving it a ⭐.
