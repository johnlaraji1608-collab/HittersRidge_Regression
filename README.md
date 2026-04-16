# Ridge_Regression
⚾ Ridge Regression on Hitters Dataset
📌 Overview

This project applies Ridge Regression (L2 Regularization) on the Hitters dataset to predict player salaries based on performance statistics.

The goal is to build a robust regression model that reduces overfitting and improves prediction accuracy.

🎯 Objective
Predict baseball player salaries
Handle multicollinearity in features
Reduce overfitting using Ridge Regression
Optimize model using cross-validation
📂 Dataset: Hitters

The Hitters dataset contains statistics of baseball players.

🔹 Features include:
Hits, Runs, Home Runs
Years of experience
At-bats, Walks
League, Division (categorical)
🎯 Target Variable:
Salary
⚙️ Data Preprocessing
Removed rows with missing Salary values
Converted categorical features using One-Hot Encoding
Filled missing values
Standardized features using scaling
🧠 What is Ridge Regression?

Ridge Regression adds an L2 penalty:

[
\text{Loss} = \text{MSE} + \alpha \sum (w^2)
]

Shrinks coefficients
Handles multicollinearity
Improves generalization
🔍 Model Implementation
Used Ridge from sklearn.linear_model
Trained model using multiple alpha values
Evaluated using cross-validation
🔄 Cross Validation
Used 5-Fold Cross Validation
Ensures model performs well on unseen data
