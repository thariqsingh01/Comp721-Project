COMP721 NBA Project: Outlier Detection and Game Outcome Prediction
Project Overview
This project delves into NBA player performance and game outcome predictions using machine learning techniques. It includes two primary modules, each implemented in separate Colab notebooks:

Outlier Detection: Identifies standout NBA players based on performance metrics.
Game Outcome Prediction: Predicts game outcomes using various classification models.
Each module is linked to the specific sections in the project report, detailing methodologies and results.

Authors
Thariq Singh - 219063421@stu.ukzn.ac.za
Saarisha Govender - 221009853@stu.ukzn.ac.za
Callyn Blayne Barath - 220010761@stu.ukzn.ac.za
Lerisha Moodley - 220036955@stu.ukzn.ac.za
Dhiya Dharampal - 221033815@stu.ukzn.ac.za
Files
1. Outlier Detection Notebook
This notebook employs various machine learning algorithms to identify NBA players whose performance metrics significantly deviate from the norm. The methods used include:

Clustering-Based Outlier Detection: Utilizes K-means clustering and Principal Component Analysis (PCA) to identify clusters and detect players with unique performance profiles.
Distance-Based Detection: Calculates performance distances to pinpoint players whose stats deviate notably from the mean.
LOESS Smoothing: Applies Local Linear Regression (LOESS) to capture nuanced performance relationships, identifying outliers within the dataset.
Key Outputs
Visualizations of outlier distributions among players.
Summary of identified outliers along with their unique performance metrics.
2. Game Outcome Prediction Notebook
This notebook predicts NBA game outcomes by training and comparing various machine learning models, including:

Random Forest Classifier: Primary model, achieving high accuracy through ensemble learning.
Support Vector Machine (SVM): Utilizes multiple kernel functions to capture complex data relationships.
Naïve Bayes and Stacking Models: Employed to compare model accuracy and boost prediction robustness.
Key Outputs
Accuracy, Precision, Recall, and F1 Scores for each model to evaluate performance.
Confusion Matrices and Feature Importance Rankings for model interpretability.
Data Preprocessing
Both notebooks share a series of common data preprocessing steps:

Data Cleaning: Handling missing values with KNN Imputation.
Feature Scaling: Standardizing data with MinMaxScaler and StandardScaler.
Dimensionality Reduction: Applying PCA to reduce feature space and improve model efficiency.
Dependencies
Python 3.7+
Libraries:
pandas
numpy
scikit-learn
matplotlib
seaborn
Report and Documentation
The complete project report, including methodology, detailed analysis, and results, is available in the GitHub repository. The report outlines the project’s objectives, data sources, model evaluations, and insights.

Usage
To run the notebooks:

Open the respective Colab notebook.
Install the necessary libraries.
Execute the cells in sequence, following any additional instructions in each notebook to view outputs.
