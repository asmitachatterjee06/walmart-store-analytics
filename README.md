# 🏬 Walmart Store Segmentation & Performance Prediction

## 📌 Business Problem

Retail businesses need to identify high-performing and underperforming stores 
to optimize strategy, improve profitability, and manage risk.

This project analyzes Walmart store-level sales data to:
- Segment stores using clustering techniques
- Predict high-performing stores using machine learning
- Identify key economic and seasonal drivers of performance

Dataset used: [Walmart Sales Dataset (Kaggle)](https://www.kaggle.com/datasets/yasserh/walmart-dataset)

---

## 📊 Dataset Description

The dataset contains weekly sales data for multiple Walmart stores along with:
- Store ID
- Weekly Sales
- Holiday Flag
- Temperature
- Fuel Price
- CPI
- Unemployment Rate

---

## 🛠 Tech Stack

- Python
- Pandas & NumPy
- Scikit-learn
- Matplotlib
- Jupyter Notebook

---

## ⚙️ Project Workflow

1. Data Cleaning & Preprocessing
2. Feature Engineering (Store-level aggregation)
3. Store Segmentation using K-Means Clustering
4. High vs Low Performer Classification (Random Forest)
5. Feature Importance Analysis

---

## 📈 Key Results

- Identified 5 distinct store segments
- Built Random Forest classifier to predict store performance
- Most influential features:
  - Average Weekly Sales
  - CPI
  - Unemployment Rate
  - Holiday Impact

---

## 📊 Model Performance

- Classification Accuracy: 89%
- Precision & Recall evaluated using classification report
- Feature importance analyzed using Random Forest

---


