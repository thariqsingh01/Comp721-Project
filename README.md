<h1>COMP721 NBA Project: Outlier Detection and Game Outcome Prediction</h1>
<h2>Project Overview</h2>
This project delves into NBA player performance and game outcome predictions using machine learning techniques. It includes two primary modules, each implemented in separate Colab notebooks:

Outlier Detection: Identifies standout NBA players based on performance metrics.
Game Outcome Prediction: Predicts game outcomes using various classification models.
Each module is linked to the specific sections in the project report, detailing methodologies and results.

<h2>Authors</h2>
<b>Thariq Singh</b> - <i>219063421@stu.ukzn.ac.za</i><p>
<b>Saarisha Govender</b> - <i>221009853@stu.ukzn.ac.za</i><p>
<b>Callyn Blayne Barath</b> - <i>220010761@stu.ukzn.ac.za</i><p>
<b>Lerisha Moodley</b> - <i>220036955@stu.ukzn.ac.za</i><p>
<b>Dhiya Dharampal</b> - <i>221033815@stu.ukzn.ac.za</i><p>

<h2>Files</h2>
<h3>1. Outlier Detection Notebook</h3>
This notebook employs various machine learning algorithms to identify NBA players whose performance metrics significantly deviate from the norm. The methods used include:

Clustering-Based Outlier Detection: Utilizes K-means clustering and Principal Component Analysis (PCA) to identify clusters and detect players with unique performance profiles.
Distance-Based Detection: Calculates performance distances to pinpoint players whose stats deviate notably from the mean.
LOESS Smoothing: Applies Local Linear Regression (LOESS) to capture nuanced performance relationships, identifying outliers within the dataset.
Key Outputs
Visualizations of outlier distributions among players.
Summary of identified outliers along with their unique performance metrics.
<h3>2. Game Outcome Prediction Notebook</h3>
This notebook predicts NBA game outcomes by training and comparing various machine learning models, including:

Random Forest Classifier: Primary model, achieving high accuracy through ensemble learning.
Support Vector Machine (SVM): Utilizes multiple kernel functions to capture complex data relationships.
Naïve Bayes and Stacking Models: Employed to compare model accuracy and boost prediction robustness.
Key Outputs
Accuracy, Precision, Recall, and F1 Scores for each model to evaluate performance.
Confusion Matrices and Feature Importance Rankings for model interpretability.
<h2>Data Preprocessing</h2>
Both notebooks share a series of common data preprocessing steps:

Data Cleaning: Handling missing values with KNN Imputation.
Feature Scaling: Standardizing data with MinMaxScaler and StandardScaler.
Dimensionality Reduction: Applying PCA to reduce feature space and improve model efficiency.
<h2>Dependencies</h2>
Python 3.7+
Libraries:
pandas
numpy
scikit-learn
matplotlib
seaborn
<h2>Report and Documentation</
The complete project report, including methodology, detailed analysis, and results, is available in the GitHub repository. The report outlines the project’s objectives, data sources, model evaluations, and insights.

<h2>Usage</h2>
To run the notebooks:

Open the respective Colab notebook.
Install the necessary libraries.
Execute the cells in sequence, following any additional instructions in each notebook to view outputs.
