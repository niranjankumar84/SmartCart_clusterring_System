# 🛒 SmartCart Customer Segmentation System

## 📌 Overview
This project focuses on building an **intelligent customer segmentation system** for an e-commerce platform (SmartCart) using **unsupervised machine learning** techniques.

The goal is to group customers into meaningful clusters based on their behavior, enabling **data-driven marketing and customer retention strategies**.

---

## 🚀 Problem Statement
SmartCart was using generic marketing strategies for all customers, which resulted in:
- Inefficient targeting
- Missed high-value customers
- Poor churn detection

To solve this, we applied **clustering techniques** to identify distinct customer segments.

---

## 📊 Dataset Description
The dataset contains **2240 customer records with 22 features** including:

### 🧑‍💼 Customer Demographics
- Year_Birth
- Education
- Marital_Status
- Income

### 🛍️ Purchase Behavior (Amount)
- MntWines, MntFruits, MntMeatProducts
- MntFishProducts, MntSweetProducts, MntGoldProds

### 📈 Purchase Behavior (Frequency)
- NumWebPurchases, NumStorePurchases
- NumCatalogPurchases, NumDealsPurchases
- NumWebVisitsMonth

### 📌 Customer Feedback
- Recency (days since last purchase)
- Complain (0/1)

---

## 🧠 Approach

### 1. Data Preprocessing
- Handling missing values
- Feature scaling
- Encoding categorical variables using OneHotEncoder

### 2. Feature Engineering
- Created meaningful features from raw data
- Removed irrelevant columns (e.g., ID)

### 3. Dimensionality Reduction
- Applied **PCA (Principal Component Analysis)** to reduce high-dimensional data

### 4. Clustering
- Applied **KMeans Clustering**
- Determined optimal number of clusters using:
  - Elbow Method (WCSS)
  - Silhouette Score

---

## 📈 Results

- Identified distinct customer segments
- Segmented customers based on:
  - Spending behavior
  - Engagement level
  - Purchase frequency

### 🔍 Key Insights
- High-value customers identified
- Low-engagement users detected
- Potential churn customers segmented
- Improved targeting strategy possible

---

## 📊 Visualization

- Elbow curve (WCSS vs K)
- Silhouette score vs K
- 3D PCA visualization of clusters

---

## 🛠️ Tech Stack

- Python 🐍
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn

---


---

## 💡 Key Learnings

- Importance of feature scaling in clustering
- Difference between WCSS and Silhouette Score
- PCA helps in visualization and noise reduction
- Clustering helps in real-world business decisions

---

## 🔥 Future Improvements

- Use advanced clustering (DBSCAN, Hierarchical)
- Deploy model using Streamlit
- Real-time customer segmentation

---

## 🤝 Contributing
Feel free to fork this repo and improve the project!

---

## 📬 Contact
If you have any questions or suggestions, feel free to connect.

