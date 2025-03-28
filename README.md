Polynomial Regression and Cross-Validation
This repository contains an in-depth analysis of Polynomial Regression, comparing different validation techniques such as Holdout Validation (Train-Test Split), Leave-One-Out Cross-Validation (LOOCV), and K-Fold Cross-Validation. The goal is to understand how different validation methods impact model performance, particularly in terms of Mean Squared Error (MSE).

📌 Project Overview
Polynomial Regression is a type of regression analysis where the relationship between the independent variable (X) and dependent variable (Y) is modeled as an n-th degree polynomial. While linear regression assumes a straight-line relationship, polynomial regression can capture more complex patterns in data.

This notebook implements Polynomial Regression on a dataset and evaluates its performance using:

Train-Test Split (Holdout Validation)

Leave-One-Out Cross-Validation (LOOCV)

K-Fold Cross-Validation (K-Fold CV)

🚀 Key Findings
Train-Test Split: MSE ~ 14, but results depend heavily on the random split.

LOOCV: MSE ~ 11.64, leveraging almost the entire dataset for training, but computationally expensive.

K-Fold CV (K=5): MSE ~ 11.22, balancing efficiency and reliability of error estimation.

Why Cross-Validation?
Cross-validation helps in reducing variance and obtaining a more generalized performance estimate, making the model less dependent on how data is split.

📂 Files in this Repository
poly_reg_and_CV.ipynb – Jupyter Notebook implementing Polynomial Regression with different cross-validation techniques.

Dataset (if applicable) – The dataset used for model training and evaluation.
