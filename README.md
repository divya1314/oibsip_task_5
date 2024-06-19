# Predicting House Prices using Linear Regression

This project aims to predict house prices using linear regression based on various features. The dataset includes columns such as `price`, `area`, `bedrooms`, `bathrooms`, `stories`, and binary categorical variables indicating house amenities and location preferences.

## Table of Contents

- [Dataset](#dataset)
- [Data Cleaning](#data-cleaning)
- [Feature Selection](#feature-selection)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Visualization](#visualization)
- [Conclusion](#conclusion)

## Dataset

The dataset used for this project is sourced from Kaggle and can be found [here](https://www.kaggle.com/code/ashydv/housing-price-prediction-linear-regression/input).

## Data Cleaning

Data cleaning involves preparing the dataset for analysis by handling missing values and ensuring data quality. Tasks include:

- **Handling Missing Values**: Removing rows with missing data to ensure accuracy in the analysis.
- **Data Integrity**: Ensuring all data is valid and in the correct format for analysis.
  
## Feature Selection

Identifying relevant features that contribute to predicting house prices. Selected features include:

- `area`
- `bedrooms`
- `bathrooms`
- `stories`
- Binary variables indicating amenities such as `mainroad`, `guestroom`, `basement`, etc.

## Model Training

Implementing linear regression using `scikit-learn` to train the predictive model on the selected features.

## Model Evaluation

Evaluating the model's performance on a test dataset using metrics such as Mean Squared Error (MSE) and R-squared.

## Visualization

Creating visualizations to illustrate the relationship between predicted and actual house prices using scatter plots.

## Conclusion

Predicting house prices using linear regression provides insights into how various features impact house prices. This approach helps in understanding market dynamics and making informed decisions in real estate.

By leveraging data cleaning, feature selection, model training, evaluation, and visualization techniques, this project offers a comprehensive analysis of predicting house prices using linear regression.

The findings from this project can assist real estate stakeholders, investors, and homeowners in pricing strategies, property valuation, and market analysis.
