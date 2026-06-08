# Ames Housing Price Prediction

## Project Overview

This project aims to predict residential housing prices using the Ames Housing dataset. Multiple machine learning models were developed and evaluated, including Linear Regression, ElasticNet, Random Forest, and Gradient Boosting.

The objective was to identify the most important factors influencing housing prices and build an accurate predictive model for property valuation.

## Business Objective

Accurate housing price predictions can support buyers, sellers, and real estate professionals in estimating property values and making informed decisions.
The project also aims to identify the most influential factors affecting housing prices and compare the performance of multiple machine learning algorithms.

## Dataset

* Dataset: Ames Housing Dataset
* Source: https://www.kaggle.com/datasets/marcopale/housing/data
* Target Variable: SalePrice

## Project Workflow

1. Exploratory Data Analysis (EDA)
2. Data Cleaning and Preprocessing
3. Baseline Model Development
4. Machine Learning Model Experiments
5. Final Model Selection
6. Cross Validation Assessment

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
* Joblib

## Repository Structure

```text
data/
notebooks/
requirements.txt
README.md
```