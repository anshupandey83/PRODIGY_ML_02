# PRODIGY_ML_02
# Customer Segmentation using K-Means Clustering

## 📌 Project Overview

This project is part of the **Prodigy InfoTech Machine Learning Internship**.

The objective of this task is to segment customers based on their **Annual Income** and **Spending Score** using the **K-Means Clustering** algorithm.

Customer segmentation helps businesses understand different groups of customers and create targeted marketing strategies.

---

## 🎯 Objective

To use K-Means clustering to divide customers into different groups based on:

- Annual Income (k$)
- Spending Score (1-100)

---

## 📊 Dataset

The dataset used is the **Mall Customer Segmentation Dataset**.

It contains information about customers such as:

- Customer ID
- Gender
- Age
- Annual Income
- Spending Score

The dataset was obtained from Kaggle.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- GitHub

---

## 🔍 Project Steps

### 1. Data Loading
The Mall Customers dataset was loaded using Pandas.

### 2. Data Cleaning
The dataset was checked for:

- Missing values
- Duplicate records
- Data types
- Basic statistical information

### 3. Exploratory Data Analysis

Different visualizations were created to understand:

- Gender distribution
- Age distribution
- Annual income distribution
- Spending score distribution

### 4. Feature Selection

The following two features were selected for clustering:

- Annual Income (k$)
- Spending Score (1-100)

### 5. Elbow Method

The Elbow Method was used to determine a suitable number of clusters by analyzing the **Within-Cluster Sum of Squares (WCSS)**.

### 6. K-Means Clustering

The K-Means algorithm was applied with **5 clusters**.

### 7. Cluster Visualization

Customers were visualized based on their Annual Income and Spending Score, with different clusters represented separately.

### 8. Cluster Analysis

The average age, annual income, and spending score of each cluster were calculated to understand customer behavior.

### 9. Silhouette Score

The Silhouette Score was calculated to evaluate the quality of the clustering.

---

## 📈 Results

The K-Means algorithm successfully divided customers into **5 distinct customer segments** based on their annual income and spending score.

The clusters can help identify groups such as:

- High-income, high-spending customers
- High-income, low-spending customers
- Low-income, high-spending customers
- Low-income, low-spending customers
- Average-income and average-spending customers

---

## 💡 Business Applications

Customer segmentation can help businesses:

- Create targeted marketing campaigns
- Identify high-value customers
- Offer personalized discounts
- Improve customer retention
- Understand customer purchasing behavior
- Develop better marketing strategies

---

## 📁 Project Files

```text
PRODIGY_ML_02/
│
├── Customer_Segmentation_KMeans.ipynb
├── Mall_Customers.csv
├── customer_segments.csv
└── README.md
