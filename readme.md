Exploring Sampling Techniques for Addressing Class Imbalance in Machine Learning
This repository contains a Jupyter Notebook that explores strategies to handle class imbalance in datasets using various sampling techniques. It evaluates the effectiveness of these methods on multiple machine learning models to identify the best practices for mitigating imbalanced data issues.

Project Objective
The goal of this project is to analyze the impact of different sampling techniques on machine learning model performance and to determine optimal approaches for addressing class imbalance in datasets.

Learning Journey
Before implementing the sampling methods, I gained foundational knowledge by experimenting with techniques to balance datasets. This included:

SMOTE (Synthetic Minority Oversampling Technique)
Tomek Links
Using the imblearn library tools:
RandomUnderSampler
RandomOverSampler
These initial experiments provided a deep understanding of the challenges and solutions related to class imbalance.

Sampling Techniques Explored
The following methods were implemented and analyzed:

Oversampling: Increases the representation of minority classes to balance the dataset.
Undersampling: Reduces the majority class to achieve class balance.
Systematic Sampling: Selects samples at fixed intervals from the dataset.
Stratified Sampling: Maintains the original class proportions in the sample.
Cluster Sampling: Samples specific clusters to create balanced datasets.
Bootstrap Sampling: Generates balanced datasets by sampling with replacement.
Machine Learning Models Evaluated
The sampling techniques were tested on these models to assess their impact:

Logistic Regression
Decision Tree
Random Forest
Support Vector Machine (SVM)
K-Nearest Neighbors (KNN)
Key Insights and Findings
Oversampling proved highly effective for datasets with significant class imbalance.
Stratified Sampling consistently maintained class proportions, ensuring reliable results.
Random Forest and Decision Tree delivered strong performance across various sampling methods.
Cluster Sampling showed promise when clusters captured meaningful data patterns.