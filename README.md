# 🛍️ Customer Segmentation Using Clustering Algorithms

This project performs customer segmentation using unsupervised machine learning techniques. The goal is to group customers based on their behavior and characteristics, enabling businesses to tailor their marketing strategies and improve customer targeting.

---

## 📊 Dataset Overview

The dataset includes the following features for each customer:

- `CustomerID`: Unique ID
- `Gender`: Male/Female
- `Age`: Age of the customer
- `Annual Income (k$)`: Income in thousands of dollars
- `Spending Score (1–100)`: Score assigned based on purchasing behavior

---

## 🎯 Project Goals

- Understand customer patterns using clustering
- Group customers based on spending habits, income, and age
- Compare multiple clustering algorithms
- Provide business-friendly interpretations of customer segments

---

## 🧠 Algorithms Used

### ✅ KMeans Clustering  
- Optimal `K` selected using the Elbow Method  
- 5 distinct clusters identified  
- Strong separation in "Income vs. Spending" dimension  

### ✅ Hierarchical Clustering  
- Dendrogram used to determine cluster cutoff  
- 5 clusters formed  
- Behaviorally similar to KMeans, but more useful for visualization  

### ✅ DBSCAN  
- Density-based approach  
- Automatically detects number of clusters and outliers  
- Identified a few meaningful groups, but sensitive to parameters

---

## 📈 Features Engineered

- All categorical data encoded (Gender)
- Data normalized using `StandardScaler`
- Plots generated for:
  - Distribution of features
  - Boxplots for outlier detection
  - Scatter plots of clusters
  - Dendrogram (for hierarchical)

---

## 🔍 Behavioral Segments (KMeans Example)

| Cluster | Description |
|---------|-------------|
| 0 | **Cautious Seniors** – Older, moderate income, conservative spending |
| 1 | **Luxury Spenders** – Young/mid-age with high income & high spending |
| 2 | **Young Budget Breakers** – Low income but high spending |
| 3 | **Balanced Millennials** – Moderate in all dimensions |
| 4 | **Wealthy Minimalists** – High income, low spending |

Each cluster was labeled based on average age, income, and spending score.

---

## 🛠️ Tools & Libraries

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib, Seaborn
- SciPy (for linkage and dendrogram)

---

## 📎 What This Project Shows

✅ Practical application of unsupervised learning  
✅ Business-facing interpretation of clusters  
✅ Multi-model comparison and performance evaluation  
✅ Strong understanding of EDA and preprocessing

---
