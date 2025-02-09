# 🎯 Customer Segmentation & Recommendation System

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://www.kaggle.com/code/abdullah7aled/customer-segmentation)

## 🚀 Problem
In this project, we delve deep into the thriving sector of online retail by analyzing a transactional dataset from a UK-based retailer, available at the **UCI Machine Learning Repository**. This dataset documents all transactions between **2010 and 2011**. 

Our primary objective is to **amplify the efficiency of marketing strategies and boost sales** through **customer segmentation**. We aim to transform the transactional data into a customer-centric dataset by **creating new features** that will facilitate the segmentation of customers into distinct groups using the **K-means clustering algorithm**.

This segmentation will allow us to **understand the distinct profiles and preferences of different customer groups**. Building upon this, we intend to **develop a recommendation system** that will suggest **top-selling products to customers within each segment who haven't purchased those items yet**, ultimately **enhancing marketing efficacy and fostering increased sales**.

## 🎯 Objectives
1. **Data Cleaning & Transformation**: Clean the dataset by handling missing values, duplicates, and outliers, preparing it for effective clustering.
2. **Feature Engineering**: Develop new features based on the transactional data to create a customer-centric dataset, setting the foundation for customer segmentation.
3. **Data Preprocessing**: Undertake feature scaling and dimensionality reduction to streamline the data, enhancing the efficiency of the clustering process.
4. **Customer Segmentation using K-Means Clustering**: Segment customers into distinct groups using K-means, facilitating targeted marketing and personalized strategies.
5. **Cluster Analysis & Evaluation**: Analyze and profile each cluster to develop targeted marketing strategies and assess the quality of the clusters formed.
6. **Recommendation System**: Implement a system to recommend best-selling products to customers within the same cluster who haven't purchased those products, aiming to boost sales and marketing effectiveness.

## 📚 Table of Contents
- **Step 1 | Setup and Initialization**
  - Step 1.1 | Importing Necessary Libraries
  - Step 1.2 | Loading the Dataset
- **Step 2 | Initial Data Analysis**
  - Step 2.1 | Dataset Overview
  - Step 2.2 | Summary Statistics
- **Step 3 | Data Cleaning & Transformation**
  - Step 3.1 | Handling Missing Values
  - Step 3.2 | Handling Duplicates
  - Step 3.3 | Treating Cancelled Transactions
  - Step 3.4 | Correcting StockCode Anomalies
  - Step 3.5 | Cleaning Description Column
  - Step 3.6 | Treating Zero Unit Prices
  - Step 3.7 | Outlier Treatment
- **Step 4 | Feature Engineering**
  - Step 4.1 | RFM Features
    - Step 4.1.1 | Recency (R)
    - Step 4.1.2 | Frequency (F)
    - Step 4.1.3 | Monetary (M)
  - Step 4.2 | Product Diversity
  - Step 4.3 | Behavioral Features
  - Step 4.4 | Geographic Features
  - Step 4.5 | Cancellation Insights
  - Step 4.6 | Seasonality & Trends
- **Step 5 | Outlier Detection and Treatment**
- **Step 6 | Correlation Analysis**
- **Step 7 | Feature Scaling**
- **Step 8 | Dimensionality Reduction**
- **Step 9 | K-Means Clustering**
  - Step 9.1 | Determining the Optimal Number of Clusters
    - Step 9.1.1 | Elbow Method
    - Step 9.1.2 | Silhouette Method
  - Step 9.2 | Clustering Model - K-means
- **Step 10 | Clustering Evaluation**
  - Step 10.1 | 3D Visualization of Top Principal Components
  - Step 10.2 | Cluster Distribution Visualization
  - Step 10.3 | Evaluation Metrics
- **Step 11 | Cluster Analysis and Profiling**
  - Step 11.1 | Radar Chart Approach
  - Step 11.2 | Histogram Chart Approach
- **Step 12 | Recommendation System**
  

## 🛠 Installation
### **1️⃣ Clone the Repository**
```sh
git clone https://github.com/abdullah-khaled0/Customer-Segmentation.git
cd Customer-Segmentation
