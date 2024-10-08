# Data Mining Techniques

This project implements various data mining techniques covered in CS235 using the Wisconsin Breast Cancer Diagnostic dataset. The goal is to explore both supervised and unsupervised learning techniques, handling challenges like dimensionality reduction, feature selection, and clustering on a real-world imbalanced dataset.

## Introduction

This project implements supervised and unsupervised data mining techniques from scratch in Python using Jupyter Notebooks. The methods are applied to the Wisconsin Breast Cancer Diagnostic dataset, focusing on techniques such as classification, dimensionality reduction, feature selection, and clustering. The project is split into two phases:

## Supervised Techniques

1. Implementing Simple Classifiers:
     - Decision Tree using Information Gain and Naive Bayes (Gaussian).
     - Performance evaluation through stratified 10-fold cross-validation and F1-score.
     - Plot: Bar chart comparing classifier performance.
2. Dimensionality Reduction with SVD:
     - Apply Singular Value Decomposition (SVD) to reduce dimensionality.
     - Evaluate classifier performance based on the SVD approximation rank.
     - Plot: Performance of classifiers vs. SVD rank.
3. Feature Selection with Randomization:
     - Randomize each feature and measure its predictive value.
     - Plot: Feature importance ranking and classifier performance using the top features.
5. Data Augmentation using SMOTE:
     - Implement SMOTE to handle class imbalance.
     - Plot: Classifier performance for varying oversampling percentages and k-values.

## Unsupervised Techniques

1. k-means Clustering:
     - Implement Lloyd’s k-means algorithm with k-means++ initialization.
     - Plot: Performance comparison between random and k-means++ initialization.
3. Density-based Clustering with DBSCAN:
     - Implement the DBSCAN algorithm.
     - Plot: Performance as a function of MinPts and Eps values.
5. Graph-based Clustering with Spectral Clustering:
     - Implement Unnormalized Spectral Clustering.
     - Plot: Performance vs. different sigma values.
7. Anomaly Detection with Isolation Forest:
     - Implement the Isolation Forest algorithm.
     - Plot: Impact on k-means clustering after removing top anomalies.

## Dataset

The project uses the Wisconsin Breast Cancer Diagnostic dataset from the UCI Machine Learning Repository.

Technologies Used

- Python for implementation.
- Jupyter Notebooks for code execution and visualization.
- Pandas for data manipulation.
- NumPy for numerical computations.
- Matplotlib for plotting results.
- Sklearn for cross-validation, F1 score calculation, and silhouette coefficient.
