# 🏡 House Price Prediction

## Project Overview

This project is based on the Kaggle competition **[House Prices: Advanced Regression Techniques](https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques)**. The goal is to predict the final sale prices of residential homes based on a variety of features such as location, size, and quality.

It is a classic regression problem and a widely used benchmark for practicing feature engineering and model evaluation.

## 1. Objective

- Input: Housing features (e.g., size, quality, location, amenities)

- Output: Predicted house price (SalePrice)

- Evaluation Metric: Root Mean Squared Error (RMSE)

## 2. Methodology

- Data Preprocessing:

Missing value imputation (median for numerical features, OneHot encoding for categorical features)

Separate pipelines for numerical and categorical features

- Modeling:

Baseline model: RandomForestRegressor (scikit-learn)

Model evaluation using Out-of-Bag (OOB) Score and validation RMSE

## 3. Results

OOB RMSE ≈ 30k

Validation RMSE ≈ 26k

This serves as a baseline performance, providing a foundation for further improvement.

## 4. Future Work

Explore advanced models: XGBoost, LightGBM, CatBoost

Enhance feature engineering (feature combinations, log-transformations, feature selection)

Perform hyperparameter tuning and cross-validation

Apply ensemble methods (Stacking / Blending)

## 5. Tech Stack

Python 3.x

Pandas / Numpy — data processing

Scikit-learn — machine learning modeling

Matplotlib / Seaborn — visualization
