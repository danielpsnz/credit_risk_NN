# Credit Card Default Prediction
## Overview:
This repository hosts a data science project focused on improving the credit risk model for credit cards within a banking environment. The risk management department has expressed dissatisfaction with the performance of their traditional statistical models and seeks to implement more advanced techniques, such as neural networks.

## Problem Statement:
The primary objective of this project is to predict the probability of credit card default among customers. Leveraging fully connected neural networks with the Sklearn library, the aim is to enhance the accuracy and reliability of credit risk assessment.

## Objectives:
* Data reading and initial analysis to ascertain the dataset's dimensions and independent variable names.
* Identification and treatment of missing values within the dataset.
* Visualization and correlation analysis, including descriptive statistics, boxplots for variable dispersion, histograms for distribution visualization, and correlation matrices.
* Standardization of data using StandardScaler.
* Dataset division into training and testing subsets.
* Implementation of a neural network model using Sklearn's MLPClassifier.
* Optimization of maximum iteration number and Alpha parameter using GridSearch.
* Representation of ROC curve for prediction evaluation.
* Thresholding of probabilities and computation of metrics such as confusion matrix, accuracy, sensitivity, and precision.

## Data Information:
The project utilizes the "default of credit card clients" dataset, comprising 24 predictor variables (X) and one continuous target variable (Y). Predictor variables include credit card limit, gender, education, age, and bank-derived flags. The target variable to predict is "default payment next month."


