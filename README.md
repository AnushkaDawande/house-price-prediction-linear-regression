# House Price Prediction Using Linear Regression

## Overview

This project develops a Simple Linear Regression model to predict residential house prices using house area as the input feature.

## Dataset

- **Dataset:** Housing Prices Dataset
- **Source:** [Kaggle – Housing Prices Dataset](https://www.kaggle.com/datasets/yasserh/housing-prices-dataset)
- **File:** `Housing.csv`
- **Domain:** Real Estate

The dataset contains house-related information such as area, bedrooms, bathrooms, stories, parking and price.

## Work Completed

1. Loaded and inspected the housing dataset.
2. Examined data types and summary statistics.
3. Identified and handled missing and invalid values.
4. Checked and removed duplicate records.
5. Selected `area` as the input feature (X).
6. Selected `price` as the target variable (Y).
7. Visualised the relationship between house area and price.
8. Split the data into 80% training and 20% testing sets.
9. Trained a Simple Linear Regression model.
10. Calculated the regression coefficient and intercept.
11. Evaluated the model using MAE, MSE, RMSE and R².
12. Compared actual and predicted house prices.
13. Generated a prediction for a new house area.

## Files

- `Housing.csv` – Original dataset.
- Completed Activity 2 notebook – Data preprocessing, model training and evaluation.
- `housing_cleaned.csv` – Cleaned dataset.
- `housing_predictions.csv` – Actual and predicted test results.

## Tools and Libraries

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Conclusion

A Simple Linear Regression model was trained to predict house prices using house area. The model was evaluated using standard regression metrics, and actual prices were compared with predicted prices. The experiment demonstrates a basic machine learning workflow for predicting continuous numerical values.

## Faculty Acknowledgement

This project was completed as part of the Machine Learning CIE 2 activity. Faculty reference and Machine Learning learning resources: [https://github.com/Princy2129](https://github.com/Princy2129)
