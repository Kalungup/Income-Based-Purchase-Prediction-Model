# Linear Regression Project

## Overview
This project applies linear regression to predict customer purchase amount based on income.

## Objective
The goal is to build and evaluate a regression model that estimates purchase amount using income as the independent variable.

## Dataset
The dataset contains 1000 observations with variables such as:
- income
- purchase_amount
- age, savings, spending_score (not used in this model)

## Methodology
- Data was loaded and cleaned
- A simple linear regression model was trained using income as the predictor
- The dataset was split into training and testing sets
- Predictions were generated and evaluated

## Model Evaluation
- R² = 0.71
- MAE ≈ 3934 SEK
- RMSE ≈ 4970 SEK
- MSE ≈ 24705526

## Interpretation
The model explains 71 percent of the variation in purchase amount, indicating a strong relationship between income and spending. However, prediction errors remain moderate, suggesting limited precision.

## Conclusion
The model is suitable for capturing general trends but not for highly accurate predictions. Performance can be improved by including additional variables such as age, savings, and spending score.

## Future Work
- Apply multiple linear regression
- Improve feature selection
- Test other machine learning models
