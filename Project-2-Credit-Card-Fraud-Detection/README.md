# Project 2 - Credit Card Fraud Detection using SMOTE

## Overview

This project was completed as part of my Decode Lab Data Analytics Internship.

The objective was to build a machine learning pipeline for detecting fraudulent credit card transactions by performing data preprocessing, exploratory data analysis, handling class imbalance using SMOTE, and evaluating multiple classification models.

---

## Dataset Information

The project uses the Credit Card Fraud Detection dataset containing anonymized transaction records.

Dataset Features:

- Time
- V1 to V28 (PCA-transformed features)
- Transaction Amount
- Class (0 = Legitimate Transaction, 1 = Fraudulent Transaction)

Total Records: **284,807**

---

## Project Workflow

1. Importing Required Libraries
2. Loading the Dataset
3. Understanding the Dataset
4. Data Quality Assessment
5. Class Distribution Analysis
6. Data Cleaning
7. Exploratory Data Analysis (EDA)
8. Data Preparation
9. Handling Class Imbalance using SMOTE
10. Model Building
11. Model Evaluation

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Jupyter Notebook

---

## Exploratory Data Analysis

The analysis includes:

- Transaction amount distribution
- Transaction time distribution
- Transaction amount by class
- Transaction time by class
- Correlation between features and fraud class
- Class imbalance visualization
- Distribution before and after applying SMOTE

---

## Machine Learning Models

Two classification models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier

Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Classification Report
- Confusion Matrix
- ROC Curve
- AUC Score

---

## Key Insights

- The dataset was highly imbalanced, with fraudulent transactions accounting for less than 1% of the total data.
- SMOTE successfully balanced both classes by generating synthetic fraud samples.
- Logistic Regression achieved strong recall while maintaining high overall accuracy.
- Decision Tree achieved better precision and F1-score compared to Logistic Regression.
- Feature correlation analysis highlighted several PCA-transformed variables with stronger relationships to fraudulent transactions.

---

## Repository Structure

```
Project-2-Credit-Card-Fraud-Detection/
│
├── decodelabs_project_2.ipynb
├── README.md
└── .gitignore
```

---

## Dataset

The dataset is not included in this repository because it exceeds GitHub's file size limit.

It can be downloaded from Kaggle:

https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

---

## How to Run

1. Clone the repository.
2. Download the dataset from Kaggle.
3. Place the dataset inside the project folder.
4. Open the notebook using Jupyter Notebook or Google Colab.
5. Install the required Python libraries.
6. Run all notebook cells sequentially.

---

## Author

**Gunjan Ahuja**

Decode Lab Data Analytics Internship