# 🧠 Customer Segmentation using Clustering

Welcome to my customer segmentation project! This repository showcases an end-to-end unsupervised learning pipeline using the **Online Retail Dataset**, where I applied various clustering algorithms to identify customer personas and uncover valuable business insights.

---

## 📁 Project Type

**Clustering (Unsupervised Learning)**

---

## 🎯 Problem Statement

The aim of this project is to segment customers based on their purchasing behavior using clustering techniques like KMeans, Agglomerative Clustering, and DBSCAN. By identifying key customer groups, businesses can improve targeting strategies, retention efforts, and revenue growth.

---

## 📊 Dataset Source

- 🗂️ **Dataset Name:** Online Retail Dataset  
- 🌐 **Source:** [Online Retail Dataset](https://archive.ics.uci.edu/ml/datasets/online+retail)

---

## 🔍 RFM Analysis

Before applying clustering models, **RFM analysis** was done to quantify customer value using three metrics:

| Metric      | Meaning                                                    |
|-------------|------------------------------------------------------------|
| **Recency** | How recently a customer made a purchase                    |
| **Frequency** | How often a customer made purchases                      |
| **Monetary** | How much money the customer has spent                     |

Each customer was scored on these metrics, and the resulting **RFM scores** were used as inputs for clustering. These features allowed for high-quality segmentation based on actual user behavior and spending patterns.

We also used **quantile-based binning** and **log transformation** to normalize skewed data, making clusters more meaningful and distinguishable.

---

## 🧾 Summary

This project focuses on customer segmentation using the Online Retail dataset. Through extensive data cleaning, RFM feature engineering, and exploratory data analysis (EDA), we revealed actionable trends and built interpretable customer clusters.

### 🔧 Key Steps:
- ✅ Data Cleaning & Preprocessing  
- 📊 EDA using the **UBM rule** (Univariate, Bivariate, Multivariate)  
- 🧮 RFM Analysis (Recency, Frequency, Monetary Value)  
- 🚀 Clustering using **KMeans**, **Agglomerative Clustering**, and **DBSCAN**  
- 📈 Visualizations using Plotly, Seaborn, and Matplotlib  
- 🔍 Cluster labeling and business insight generation

---

## 🧪 Models Used

| Model                    | Role                                     |
|--------------------------|------------------------------------------|
| KMeans                   | Main segmentation model ✅ (Final Model) |
| Agglomerative Clustering | Validated consistency of segments        |
| DBSCAN                   | Detected noise and dense subgroups       |

---

## ✅ Final Model Chosen

- 📌 **Model:** KMeans Clustering  
- 📊 **Input Features Used:** 3 columns (`Recency`, `Frequency`, `Monetary`)  
- 📈 **Silhouette Score:** `0.433`  
- 🔍 **Optimal Clusters:** 2 
- 💬 Chosen due to balanced interpretability, cluster compactness, and clear business mapping.

---

## 🧠 Key Insights

- Identified **high-value customers ("Champions")** using RFM scores.
- Discovered **at-churn** and **loyal** customer segments for marketing action.
- Found seasonal trends and purchase patterns via monthly analysis.
- Visualized all clusters using 2D and 3D charts for better storytelling.

---

## 🖼️ Sample Visualizations

- 📦 Product purchase trends
- 📅 Monthly revenue trends
- 📈 3D cluster plots
- 🔁 RFM-based loyalty segmentation

---

## 📎 Tech Stack

- Python
- Pandas, NumPy
- Seaborn, Matplotlib, Plotly
- Scikit-learn
- Yellowbrick
- WordCloud
- Colab / Jupyter Notebook

---


