## TV Sales Prediction API
This project provides a FastAPI-based API to predict TV sales based on a linear regression model trained on a dataset of TV advertising spend and sales. The model is built using Python, leveraging FastAPI for the API endpoint, and scikit-learn for machine learning.

## Problem Statement
The goal is to predict sales based on TV marketing expenses using different machine learning techniques, including:

Linear Regression
Decision Trees
Random Forests
Gradient Descent Optimization

## Project Overview
This project provides a simple linear regression model for predicting TV sales based on TV advertisement spending. The model uses FastAPI to expose the model as an API endpoint, allowing users to input TV advertising spend and receive a prediction for the expected sales.

## Dataset
The dataset used for training is tvmarketing.csv, which contains two columns:

TV: Amount spent on TV advertising.
Sales: Sales outcome (target variable).

## The project includes:
Linear Regression Model: Trained using scikit-learn's LinearRegression.
Gradient Descent: Implemented manually to optimize the slope (m) and intercept (b) values.
Model Comparison: Comparison of Linear Regression, Decision Tree, and Random Forest models based on Root Mean Square Error (RMSE).
The model with the best performance is used in the API endpoint for predictions.

## API Endpoint
The FastAPI application exposes a single POST endpoint:

/predict/: Accepts JSON input with the tv field (TV advertising spend) and returns a JSON response with the predicted sales.
