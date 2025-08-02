# Instacart Market Basket Analysis 🛒

This repository contains a set of Jupyter Notebooks tackling the **Instacart Market Basket Analysis** challenge. The dataset used is a rich, relational collection of files representing customer orders over time, anonymized and sampled from over **3 million grocery orders** by **200,000+ Instacart users**.

The primary objective is to **predict which products a user will order next**, based on their purchase history and behavioral patterns.

---

## 📁 Notebooks

1. **Data Exploration**
   - Explores and visualizes the raw datasets.
   - Understands product frequency, reorder patterns, and temporal trends.

2. **Customer Segmentation**
   - Applies **Principal Component Analysis (PCA)** for dimensionality reduction.
   - Uses **K-Means Clustering** to segment users based on purchasing behavior.

3. **Association Rule Mining**
   - Uses the **Apriori algorithm** to mine association rules.
   - Identifies product combinations and frequent itemsets.

---

## 📊 Dataset Description

For each user, the dataset provides:
- Between **4 to 100** prior orders
- **Product sequences** within each order
- **Weekday and hour** of purchase
- **Time gap** between consecutive orders

This structured and time-aware dataset allows for powerful analysis of customer behavior and preferences.

---

Feel free to explore the notebooks to understand how different ML techniques can be applied in a real-world retail setting.
