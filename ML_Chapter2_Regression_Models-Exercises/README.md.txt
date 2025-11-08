# Machine Learning – Chapter 2: Regression Models

This project was completed as part of the **Machine Learning and Data Science** course at **EDHEC Business School (Nice, France)**.  
It explores and implements various **regression techniques**, providing both theoretical background and practical Python applications.

## 📘 Overview

Regression analysis is a cornerstone of statistical learning and predictive analytics.  
This notebook introduces:
- **Linear and non-linear regression models**
- **Loss functions and regularization**
- **Model evaluation and selection (AIC, BIC, Cross-validation)**
- **Gradient descent optimization**
- **Hands-on examples of linear and nonlinear regression**

Two key examples demonstrate the full regression workflow:
1. **Simple Linear Regression** – implementing gradient descent manually and validating against `scikit-learn`
2. **Nonlinear Regression (Damped Harmonic Oscillator)** – modeling complex, non-linear relationships with iterative parameter optimization

## 🧠 Learning Objectives

- Understand and compare regression methods (parametric vs non-parametric)
- Derive and minimize key loss functions (MSE, MAE, Huber, Quantile)
- Apply **L1 (Lasso)**, **L2 (Ridge)**, and **Elastic Net** regularization
- Implement gradient-based optimization algorithms
- Evaluate model quality with **cross-validation**, **AIC/BIC**, and **residual analysis**
- Balance the **bias–variance tradeoff** for model generalization

## 🧰 Technologies and Tools

- **Python 3**
- **NumPy**, **pandas**
- **matplotlib**, **seaborn**
- **scikit-learn**, **statsmodels**
- **Jupyter Notebook**

## 🧩 Practical Exercises

### 1. Simple Linear Regression
- Generate synthetic linear data with noise  
- Implement gradient descent from scratch to learn parameters (θ₀, θ₁)  
- Compare results with `scikit-learn`’s `LinearRegression` model  
- Evaluate training/test MSE and R² scores  
- Perform residual analysis and outlier detection  

### 2. Nonlinear Regression – Damped Harmonic Oscillator
- Simulate data from the physical model  
