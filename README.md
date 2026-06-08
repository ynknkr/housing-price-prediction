# Ames Housing Price Prediction

## Project Overview

This project aims to predict residential housing prices using the Ames Housing dataset. Multiple machine learning models were developed and evaluated, including Linear Regression, ElasticNet, Random Forest, and Gradient Boosting.

The objective was to identify the most important factors influencing housing prices and build an accurate predictive model for property valuation.

## Business Objective

Accurate housing price predictions can support buyers, sellers, and real estate professionals in estimating property values and making informed decisions.

## Dataset

* Dataset: Ames Housing Dataset
* Target Variable: SalePrice

## Project Workflow

1. Exploratory Data Analysis (EDA)
2. Data Cleaning and Preprocessing
3. Log Transformation
4. Feature Encoding and Scaling
5. Baseline Model Development
6. Model Experimentation
7. Final Model Selection
8. Cross Validation Assessment

## Models Evaluated

* Dummy Regressor
* Linear Regression
* ElasticNet
* Random Forest
* Gradient Boosting

## Final Model

Gradient Boosting was selected as the final model.

### Final Performance

| Metric                | Value   |
| --------------------- | ------- |
| Test RMSE (Log Scale) | 0.147   |
| Test MAE (Log Scale)  | 0.100   |
| Test R²               | 0.886   |
| RMSE (Original Scale) | $33,401 |
| MAE (Original Scale)  | $18,766 |

## Key Findings

* Overall Quality was the most important predictor of housing prices.
* Living Area strongly influenced property values.
* Kitchen Quality, Basement Size, and Construction Year contributed significantly to predictions.
* Gradient Boosting achieved the strongest overall performance among all evaluated models.

## Tools and Libraries

* Python
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* XGBoost
* Joblib

## Repository Structure

```text
data/
notebooks/
outputs/
src/
requirements.txt
README.md
```