<h1>COMP721 NBA Project: Outlier Detection and Game Outcome Prediction</h1> 

<h2>Project Overview</h2>
<p>This project delves into NBA player performance and game outcome predictions using machine learning techniques. It includes two primary modules, each implemented in separate Colab notebooks:</p>
<ul> 
  <li><b>Outlier Detection</b>: Identifies standout NBA players based on performance metrics.</li>
  <li><b>Game Outcome Prediction</b>: Predicts game outcomes using various classification models.</li> 
</ul> 
<p>Each module is linked to specific sections in the project report, detailing methodologies and results.</p>

<h2>Authors</h2> 
<ul>
  <li><b>Thariq Singh</b> - <i>219063421@stu.ukzn.ac.za</i></li>
  <li><b>Saarisha Govender</b> - <i>221009853@stu.ukzn.ac.za</i></li>
  <li><b>Callyn Blayne Barath</b> - <i>220010761@stu.ukzn.ac.za</i></li> 
  <li><b>Lerisha Moodley</b> - <i>220036955@stu.ukzn.ac.za</i></li> 
  <li><b>Dhiya Dharampal</b> - <i>221033815@stu.ukzn.ac.za</i></li> 
</ul> 

<h2>Files</h2>

<h3>1. Outlier Detection Notebook</h3>
<p>This notebook employs various machine learning algorithms to identify NBA players whose performance metrics significantly deviate from the norm. The methods used include:</p>
<ul> 
  <li><b>Clustering-Based Outlier Detection</b>: Utilizes K-means clustering and Principal Component Analysis (PCA) to identify clusters and detect players with unique performance profiles.</li>
  <li><b>Distance-Based Detection</b>: Calculates performance distances to pinpoint players whose stats deviate notably from the mean.</li> 
  <li><b>LOESS Smoothing</b>: Applies Local Linear Regression (LOESS) to capture nuanced performance relationships, identifying outliers within the dataset.</li>
</ul> 

<h4>Key Outputs</h4>
<ul> 
  <li>Visualizations of outlier distributions among players.</li>
  <li>Summary of identified outliers along with their unique performance metrics.</li>
</ul>

<h3>2. Game Outcome Prediction Notebook</h3>
<p>This notebook predicts NBA game outcomes by training and comparing various machine learning models, including:</p> 
<ul> 
  <li><b>Random Forest Classifier</b>: Primary model, achieving high accuracy through ensemble learning.</li>
  <li><b>Support Vector Machine (SVM)</b>: Utilizes multiple kernel functions to capture complex data relationships.</li>
  <li><b>Naïve Bayes and Stacking Models</b>: Employed to compare model accuracy and boost prediction robustness.</li> 
</ul> 

<h4>Key Outputs</h4>
<ul> 
  <li>Accuracy, Precision, Recall, and F1 Scores for each model to evaluate performance.</li>
  <li>Confusion Matrices and Feature Importance Rankings for model interpretability.</li> 
</ul> 

<h2>Data Preprocessing</h2> 
<p>Both notebooks share a series of common data preprocessing steps:</p>
<ul>
  <li><b>Data Cleaning</b>: Handling missing values with KNN Imputation.</li> 
  <li><b>Feature Scaling</b>: Standardizing data with MinMaxScaler and StandardScaler.</li> 
  <li><b>Dimensionality Reduction</b>: Applying PCA to reduce feature space and improve model efficiency.</li> 
</ul> 

<h2>Dependencies</h2> 
<p>Ensure that the following dependencies are installed:</p>
<ul> 
  <li><b>Python</b> 3.7+</li> 
  <li>Libraries: 
    <ul> 
      <li>pandas</li> 
      <li>numpy</li> <li>scikit-learn</li>
      <li>matplotlib</li> <li>seaborn</li> 
    </ul>
  </li> 
</ul>

<h2>Report and Documentation</h2> 
<p>The complete project report, including methodology, detailed analysis, and results, is available in the <a href="https://github.com/thariqsingh01/Comp721-Project">GitHub repository</a>. The report outlines the project’s objectives, data sources, model evaluations, and insights.</p>

<h2>Usage</h2> 
<p>To run the notebooks:</p> 
<ol> 
  <li>Open the respective Colab notebook.</li> 
  <li>Install the necessary libraries.</li> 
  <li>Upload the necessary textfiles.</li>
  <li>Execute the cells in sequence.</li> 
</ol>
