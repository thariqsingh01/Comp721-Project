COMP721 NBA Project: Outlier Detection and Game Outcome Prediction
Project Overview
This project focuses on NBA player performance and game predictions using machine learning techniques. It includes two primary modules: one for outlier detection of NBA players and the other for game outcome prediction. Each module is implemented in separate Colab notebooks, linked to specific sections of the project report.

Authors
Thariq Singh - 219063421@stu.ukzn.ac.za
Saarisha Govender - 221009853@stu.ukzn.ac.za
Callyn Blayne Barath - 220010761@stu.ukzn.ac.za
Lerisha Moodley - 220036955@stu.ukzn.ac.za
Dhiya Dharampal - 221033815@stu.ukzn.ac.za
Files
1. Outlier Detection Notebook
The outlier detection notebook uses various machine learning algorithms to identify standout players based on their performance metrics. The methods include:

Clustering-Based Outlier Detection: Utilizes K-means clustering and Principal Component Analysis (PCA) to group similar players and identify those who perform above or below the norm.
Distance-Based Detection: Measures player performance distances to detect those significantly deviating from the mean.
LOESS Smoothing: Applies Local Linear Regression to capture nuanced relationships, identifying outliers in performance metrics.
Key Outputs
Visualizations of outlier player distributions.
Summary of top outliers and their performance metrics.
2. Game Outcome Prediction Notebook
This notebook focuses on predicting NBA game outcomes using machine learning classification models, including:

Random Forest: The primary model, achieving high accuracy through ensemble learning.
Support Vector Machine (SVM) with multiple kernel functions.
Naïve Bayes and Stacking Models: Used to compare performance and ensemble prediction accuracy.
Key Outputs
Accuracy, precision, recall, and F1 scores for each model.
Confusion matrices and feature importance rankings for better model interpretability.
Data Preprocessing
Both notebooks share common preprocessing steps:

Data Cleaning: Handling missing values with KNN Imputation.
Feature Scaling: Using MinMaxScaler and StandardScaler to standardize data.
Dimensionality Reduction: Applying PCA to reduce feature space and improve model efficiency.
Dependencies
Python 3.7+
Libraries: pandas, numpy, scikit-learn, matplotlib, seaborn
Report and Documentation
The full report, including methodology, analysis, and detailed results, is available here. This document outlines the project objectives, data sources, model evaluations, and findings.

Usage
To run the notebooks:

Load the respective Colab notebook.
Ensure the necessary libraries are installed.
Follow the instructions within each notebook to execute the cells and view outputs.
