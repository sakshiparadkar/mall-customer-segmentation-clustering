 Mall Customer Segmentation using Clustering & PCA
📌 Project Overview

This project focuses on Customer Segmentation using unsupervised machine learning techniques. The goal is to analyze customer behavior and group customers into meaningful clusters based on their purchasing patterns.

Customer segmentation helps businesses understand different types of customers and design targeted marketing strategies.

🎯 Objectives

Perform Exploratory Data Analysis (EDA) on customer data.

Apply multiple clustering algorithms to identify customer groups.

Determine the optimal number of clusters.

Reduce dimensionality using Principal Component Analysis (PCA).

Visualize customer segments for better interpretation.

📊 Dataset

The dataset contains mall customer information including:

Customer ID

Gender

Age

Annual Income (k$)

Spending Score (1–100)

These features help analyze customer purchasing behavior.

⚙️ Technologies Used

Python

Pandas & NumPy – Data manipulation

Matplotlib & Seaborn – Data visualization

Scikit-learn – Machine learning algorithms

Jupyter Notebook

🔎 Data Preprocessing

Checked missing values

Feature selection

Data scaling using StandardScaler

Prepared dataset for clustering algorithms

🤖 Machine Learning Models Used
1️⃣ K-Means Clustering

Applied Elbow Method to find optimal number of clusters.

Segmented customers based on income and spending patterns.

2️⃣ DBSCAN

Density-based clustering method.

Identified noise and outlier customers.

3️⃣ Hierarchical Clustering

Used dendrogram to visualize cluster formation.

Compared clustering structure with K-Means results.

📉 Dimensionality Reduction (PCA)

Applied Principal Component Analysis (PCA).

Reduced dataset dimensions for visualization.

Improved cluster visualization in 2D space.

📈 Results & Insights

The clustering analysis revealed distinct customer groups such as:

High income – high spending customers (Premium customers)

High income – low spending customers (Potential targets)

Low income – high spending customers

Budget-conscious customers

These insights can help businesses:

Improve marketing strategies

Personalize promotions

Increase customer retention

📊 Visualizations

Elbow Method Graph

Cluster Scatter Plots

PCA Visualization

Dendrogram (Hierarchical Clustering)
