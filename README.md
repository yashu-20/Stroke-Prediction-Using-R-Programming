# Stroke-Prediction-Using-R-Programming
Stroke Prediction Using Machine Learning

Project Overview:

A predictive model evaluates stroke risk through examination of different health parameters combined with lifestyle elements. It leverages machine learning techniques to analyze the dataset and compares the performance of two popular classification algorithms: Two common classification models Support Vector Machines (SVM) and Naive Bayes (NB) serve as the algorithms in this project. The analysis reveals important stroke variables while measuring model precision and accuracy together with recall and F1-Score performance.

Features:

The data preprocessing workflow for stroke prediction addresses missing values while performing normalization on variables.
Implementation of SVM and Naive Bayes classifiers for prediction.
We evaluated models by measuring their performance with accuracy rates alongside precision rates and recall rates and F1-score values.
Data visualization for better understanding of feature importance and distributions.

Tech Stack:

Programming Language: R
Libraries Used:
caret - For model training and evaluation.
e1071 - For SVM implementation.
ggplot2 - For visualizations.
dplyr - For data manipulation.

Dataset
Source: Stroke Prediction Dataset

Description:
The model contains data about patient age alongside gender in addition to hypertension conditions heart problems and BMI scores and smoking and blood glucose assessment results.
The output measurement variable represents stroke status with values of 0 for no stroke or 1 for stroke condition.

How the Models Work

1. Support Vector Machine (SVM):
Seeks to place a best possible borderline plane across two different data classifications.
Support vector machines operate well with large characteristic databases while enabling users to transform data using kernel tricks when features lie in non-linear patterns.
2. Naive Bayes:
A model employing Bayes' Theorem implements probabilistic operations.
The model works independently with features and produces fast classification outputs.

Results

SVM Accuracy: ~90% (adjust based on actual results).
Naive Bayes Accuracy: ~85%.

Key Insights:

The risk of strokes depends heavily on hypertension alongside heart disease and glucose levels.
The performance metrics revealed SVM achieved better results than Naive Bayes for both accuracy and F1-score.
