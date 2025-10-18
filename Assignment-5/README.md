# Machine Learning (UML501) - Assignment 5

## Q1: Ridge Regression with Gradient Descent Optimization
Generate a dataset with at least seven highly correlated columns and a target variable. Implement Ridge Regression using Gradient Descent Optimization. Take different values of learning rate (0.0001, 0.001, 0.01, 0.1, 1, 10) and regularization parameter (10^-15, 10^-10, 10^-5, 10^-3, 0, 1, 10, 20). Choose the best parameters for which the ridge regression cost function is minimum and the R2_score is maximum.

## Q2: Hitters Dataset Analysis
Load the Hitters dataset from: https://drive.google.com/file/d/1qzCKF6JKKMB0p7ul_lLy8tdmRk3vE_bG/view?usp=sharing

(a) Pre-process the data (handle null values, noise, categorical to numerical encoding).
(b) Separate input and output features and perform scaling.
(c) Fit a Linear, Ridge (using regularization parameter as 0.5748), and LASSO (using regularization parameter as 0.5748) regression function on the dataset.
(d) Evaluate the performance of each trained model on the test set. Determine which model performs the best and explain why.

## Q3: Cross Validation for Ridge and Lasso Regression
Explore Ridge Cross Validation (RidgeCV) and Lasso Cross Validation (LassoCV) functions of Python. Implement both on the Boston House Prediction Dataset (using load_boston dataset from sklearn.datasets).

## Q4: Multiclass Logistic Regression
Implement Multiclass Logistic Regression (step-by-step) on the Iris dataset using a one vs. rest strategy.
