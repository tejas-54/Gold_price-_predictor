# Gold Price Prediction Project

## Overview
This project aims to predict gold prices using machine learning models, including Decision Tree, Random Forest, Extra Trees, and XGBoost. After data preprocessing and feature selection, the models are trained and evaluated, with the Extra Trees Regressor achieving the highest accuracy.

## Problem Approach
The main goal is to accurately predict gold prices by leveraging financial indicators. The code performs:
- Data preprocessing
- Exploratory data analysis (EDA)
- Outlier detection and feature selection
- Model training, evaluation, and hyperparameter tuning

## Feature Selection and Explanation
The key features used in this project are:
- **Date**: Contextualizes data over time.
- **SPX (S&P 500 Index)**: Tracks the stock market's influence on gold prices, as gold often inversely correlates with stock indices during market volatility.
- **USO (Oil Prices)**: Oil prices impact inflation trends, indirectly influencing gold prices as an inflation hedge.
- **EUR/USD (Currency Exchange Rate)**: Reflects currency fluctuations that affect global gold prices.
- **SLV (Silver Prices)**: Silver and gold follow similar market trends, enhancing predictive accuracy.

## Data Analysis and Visualization
1. **EDA**: Visualizes feature distributions and relationships through pair plots and correlation heatmaps.
2. **Outlier Detection**: Calculates outliers using the interquartile range (IQR), ensuring data consistency without skewing model predictions.

## Model Training and Selection
The following models are trained and evaluated:
- **Decision Tree Regressor**
- **Random Forest Regressor**
- **XGBoost Regressor**
- **Extra Trees Regressor**

Each model’s performance is evaluated using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), R-squared (R2), and cross-validation scores. The **Extra Trees Regressor** outperformed other models, demonstrating the highest accuracy.

## Hyperparameter Tuning
Hyperparameter tuning for the Extra Trees Regressor uses **RandomizedSearchCV** to optimize parameters such as the number of estimators, max depth, and max features. The model is retrained with these parameters to improve its accuracy further.

## Results Visualization
The code plots the actual vs. predicted gold prices, enabling a visual comparison of the model’s predictions against real values and demonstrating its effectiveness in trend prediction.

## Summary
This project takes a structured approach to gold price prediction by selecting relevant financial indicators, performing detailed analysis, and applying machine learning models. The Extra Trees Regressor was ultimately chosen for its accuracy, making it the recommended model for this task.

With the **"Extra Trees Regressor"**, the model achieved a prediction accuracy of **"99.527%"** for gold prices. This result highlights the model’s effectiveness in identifying and leveraging key patterns and relationships within the dataset.
![image](https://github.com/user-attachments/assets/876229fe-5e36-43f3-a4d4-6cf9161fca02)
![image](https://github.com/user-attachments/assets/df6cac16-d98e-42b7-adf0-2455c5442020)

