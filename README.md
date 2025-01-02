# Credit-Card-Fraud-Detection

# Overview
Fraudulent transactions cost the world billions every year. I took on the challenge to create a robust, cutting-edge fraud detection system that combines advanced techniques with real-world applicability. Here's what makes this project shine:

This project explores the use of machine learning techniques to detect fraudulent credit card transactions. It utilizes a highly imbalanced dataset containing real-world transaction data, where fraudulent cases constitute a minor proportion.

The project's objective is to enhance the detection of fraudulent transactions while minimizing false positives.

<img width="800" height="400" alt="Screenshot 2025-01-02 at 8 33 14 PM" src="https://github.com/user-attachments/assets/22c507e1-10bf-4def-87c4-65703ce5c470" />


# Key Features

Dataset: European cardholder transactions with 284,807 entries and 31 features, including PCA-transformed components.

Techniques Used: Data scaling, outlier removal, and imbalanced data handling with SMOTE.

Algorithms: Logistic Regression, Support Vector Machine, K-Nearest Neighbors, Naive Bayes, and Random Forest.

Evaluation Metrics: Precision, Recall, F1 Score, ROC AUC.

# Workflow

Data Preprocessing:

Checked for missing values (none found).

Scaled the Time and Amount features using RobustScaler.

Addressed imbalanced data via SMOTE applied to the training set.

Exploratory Data Analysis:

Visualized correlations using heatmaps.

Identified key features contributing to fraud detection.

Removed outliers in critical features (e.g., V10, V12, V14) using the IQR method.

Modeling:

Trained models using Stratified K-Fold cross-validation.

Evaluated performance with metrics and ROC curves.

Conducted hyperparameter tuning for Logistic Regression and Random Forest.

# Results:

Random Forest and Logistic Regression achieved the highest ROC AUC scores (0.97+).

Tools and Libraries

Languages: Python

Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

Environment: Kaggle

<img width="717" alt="Screenshot 2025-01-02 at 8 30 13 PM" src="https://github.com/user-attachments/assets/4aa0a11b-c8bb-4c4e-a388-5aed5380306a" />


# How to Run

Clone the repository:

git clone https://github.com/randhir-05/Credit-Card-Fraud-Detection

Install dependencies:

pip install -r requirements.txt

Run the notebook in your preferred environment.

Acknowledgments

Dataset sourced from the Kaggle Credit Card Fraud Detection competition.
