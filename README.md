# 🧩 Task 2 — K-Means Clustering: Customer Segmentation  
**Machine Learning Internship Project**

---

## 📘 Project Overview  
This project focuses on **Customer Segmentation using K-Means Clustering** with the *Mall Customers* dataset.  
The aim is to group customers based on their **Annual Income** and **Spending Score** to help businesses understand customer behavior and plan targeted marketing strategies.

---

## 🧠 Objective  
To identify distinct customer groups with similar spending habits using the **K-Means clustering algorithm** and visualize these patterns for better business insights.

---

## 📂 Dataset  
**Dataset Name:** Mall_Customers.csv  
**Source:** [Download Dataset (GitHub Gist)](https://gist.github.com/pravalliyaram/5c05f43d2351249927b8a3f3cc3e5ecf/raw/17c6cc1a1b8e3ef4e75e15b55a97df04d3f80a77/Mall_Customers.csv)

### Dataset Information  
- **CustomerID:** Unique ID for each customer  
- **Gender:** Male/Female  
- **Age:** Age of the customer  
- **Annual Income (k$):** Annual income in thousands  
- **Spending Score (1-100):** Score assigned by the mall based on spending behavior  

---

## ⚙️ Technologies Used  
- Python 🐍  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 🧾 Steps Performed  
1. **Data Loading and Exploration**  
   - Loaded the dataset and checked for missing values.  
2. **Feature Selection**  
   - Selected `Annual Income (k$)` and `Spending Score (1-100)` as key features.  
3. **Feature Scaling**  
   - Standardized features using `StandardScaler` for better clustering accuracy.  
4. **Finding Optimal Clusters**  
   - Used the **Elbow Method** to determine the best number of clusters.  
5. **Model Training**  
   - Implemented **K-Means clustering** with `k=5`.  
6. **Visualization and Insights**  
   - Visualized clusters to understand customer segmentation patterns.  

---

## 📊 Results  
- Optimal number of clusters: **5**  
- Customers were successfully grouped into segments with distinct income and spending characteristics.  

### Cluster Insights  
| Cluster | Description |
|----------|--------------|
| 0 | High Income – High Spending |
| 1 | Low Income – Low Spending |
| 2 | High Income – Low Spending |
| 3 | Average Income – Average Spending |
| 4 | Low Income – High Spending |

---


