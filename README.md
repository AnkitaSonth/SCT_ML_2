
# 🧩 Task 2 — K-Means Clustering: Customer Segmentation
**Machine Learning Internship Project**

---

## 📘 Project Overview
This project performs **Customer Segmentation using K-Means Clustering** on the popular *Mall Customers* dataset.  
The goal is to group customers into different segments based on their **Annual Income** and **Spending Score**, which helps businesses understand purchasing patterns and target specific groups effectively.

---

## 🧠 Objective
To identify customer groups with similar behavior using K-Means clustering algorithm and visualize the results for better business insights.

---

## 📂 Dataset
**Dataset Name:** Mall_Customers.csv  
**Source:** [Download Dataset (GitHub Gist)](https://gist.github.com/pravalliyaram/5c05f43d2351249927b8a3f3cc3e5ecf/raw/17c6cc1a1b8e3ef4e75e15b55a97df04d3f80a77/Mall_Customers.csv)

### Dataset Information
- **CustomerID:** Unique ID assigned to each customer  
- **Gender:** Male/Female  
- **Age:** Age of the customer  
- **Annual Income (k$):** Annual income of the customer in thousands  
- **Spending Score (1-100):** Score assigned by the mall based on customer behavior and spending nature  

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
   - Selected relevant features: `Annual Income (k$)` and `Spending Score (1-100)`.
3. **Feature Scaling**
   - Standardized features using `StandardScaler` for better clustering performance.
4. **Finding Optimal Clusters**
   - Used the **Elbow Method** to determine the best value of *k*.
5. **Applying K-Means**
   - Trained the K-Means model with `k=5`.
6. **Visualization**
   - Visualized clusters using a scatter plot with distinct colors for each cluster.

---

## 📊 Results
- Optimal number of clusters: **5**
- Each cluster represents customers with similar **income** and **spending behavior**.
- The cluster centroids indicate spending trends:
  - Cluster 0: High income, high spending  
  - Cluster 1: Low income, low spending  
  - Cluster 2: High income, low spending  
  - Cluster 3: Average income, average spending  
  - Cluster 4: Low income, high spending  

---

## 📈 Visualizations
### Elbow Method
Shows the optimal number of clusters based on inertia values.

![Elbow Plot](outputs/elbow_plot.png)

### Customer Segments
Visualization of customers grouped by K-Means clustering.

![Clusters](outputs/clusters_plot.png)

---

## 💻 How to Run
### Clone the Repository
```bash
git clone https://github.com/YOUR_USERNAME/customer-segmentation-kmeans.git
cd customer-segmentation-kmeans
