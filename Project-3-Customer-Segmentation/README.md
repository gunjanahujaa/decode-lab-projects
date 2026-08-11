# Project 3 - Customer Segmentation using Unsupervised Learning

## Overview

This project was completed as part of my Decode Lab Data Analytics Internship.

The objective was to perform customer segmentation using unsupervised learning techniques by applying data cleaning, feature engineering, feature scaling, Principal Component Analysis (PCA), and K-Means clustering to identify meaningful customer groups and extract business insights.

---

## Dataset Information

The dataset contains information about customers, including:

- Year of Birth
- Education
- Marital Status
- Income
- Number of Children
- Customer Recency
- Product Purchases
- Deal Purchases
- Web Purchases
- Catalog Purchases
- Store Purchases
- Web Visits
- Campaign Responses

Total Records: **2240**

---

## Project Workflow

1. Importing Required Libraries
2. Loading the Dataset
3. Understanding the Dataset
4. Data Quality Assessment
5. Data Cleaning
6. Feature Engineering
7. Feature Selection
8. Feature Scaling
9. Principal Component Analysis (PCA)
10. Choosing the Optimal Number of Clusters
11. Final K-Means Clustering
12. Cluster-wise Comparison
13. Final Cluster Profiling

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Data Cleaning

The dataset was checked for:

- Missing values
- Duplicate rows
- Duplicate customer IDs
- Suspicious Year of Birth values
- Suspicious Marital Status values
- Unusual Income values

Missing Income records and invalid Year of Birth records were handled during the data cleaning process.

After cleaning, the dataset contained **2214 customer records**.

---

## Feature Engineering

New features were created to better represent customer behavior:

- Total Spending
- Total Purchases
- Total Children
- Customer Age

These features were used along with customer income, purchasing behavior, website activity, and recency for customer segmentation.

---

## Customer Segmentation

The following features were selected for clustering:

- Income
- Age
- Total Children
- Total Spending
- Total Purchases
- NumWebVisitsMonth
- NumDealsPurchases
- NumWebPurchases
- NumCatalogPurchases
- NumStorePurchases
- Recency

The selected features were standardized using `StandardScaler` before applying PCA and K-Means clustering.

PCA was then used to reduce the dimensionality of the feature space while retaining the majority of the information in the dataset.

---

## Cluster Analysis

The optimal number of clusters was evaluated using:

- Elbow Method
- Silhouette Score

Based on the analysis, **2 clusters** were selected for the final K-Means model.

The resulting customers were divided into:

- High-Value Customers
- Low-Value Customers

---

## Key Insights

- High-Value Customers represented approximately **46.93%** of the customer base.
- Low-Value Customers represented approximately **53.07%** of the customer base.
- High-Value Customers had a significantly higher average income.
- High-Value Customers showed substantially higher total spending.
- High-Value Customers had a higher average number of purchases.
- High-Value Customers showed greater purchasing activity across web, catalog, and store channels.
- Low-Value Customers represented the larger customer segment but showed comparatively lower spending and purchasing activity.
- Income and purchasing behavior were important factors in distinguishing the two customer segments.


---

## How to Run

1. Clone the repository.
2. Download the `marketing_campaign.csv` dataset and place it in the same directory as the notebook.
3. Open the notebook using Jupyter Notebook or Google Colab.
4. Install the required Python libraries.
5. Run all notebook cells sequentially.

---

## Author

**Gunjan Ahuja**

Decode Lab Data Science Intern
