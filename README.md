# Linear Regression from Scratch (Python)

### Project Overview

This project implements Linear Regression from scratch using Python, without relying on machine learning libraries like Scikit-learn. The goal of this project is to understand the core mathematics behind linear regression, including gradient descent and parameter optimization. This implementation demonstrates how a model learns the relationship between input features and target values by minimizing the prediction error.

### Objective

The main objectives of this project are:
* Understand how Linear Regression works internally
* Implement Gradient Descent for parameter optimization
* Learn how model parameters (weights and bias) are updated during training
* Build intuition for loss functions and optimization

### Mathematical Background

Linear Regression tries to learn the relationship between input feature X and output y using the equation:

y = wx + b

Where:
* w = weight (slope)
* b = bias (intercept)
* x = input feature
* y = predicted output

The model learns the optimal w and b by minimizing the Mean Squared Error (MSE):

$$MSE = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2$$

Gradient Descent is used to iteratively update the parameters.
