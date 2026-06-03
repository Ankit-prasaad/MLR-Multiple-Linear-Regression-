# MLR-Multiple-Linear-Regression
# Toyota Corolla Price Prediction Using Multiple Linear Regression

## Project Overview

This project focuses on predicting the market price of Toyota Corolla vehicles using Multiple Linear Regression and regularized regression techniques. The objective is to identify the key factors influencing car prices and develop an accurate predictive model through a structured machine learning workflow.

The project covers data preprocessing, exploratory data analysis, feature engineering, multicollinearity assessment, feature selection, model training, and performance evaluation.

## Objectives

* Analyze the relationship between vehicle characteristics and selling price.
* Build a Multiple Linear Regression model for price prediction.
* Evaluate the impact of different features on model performance.
* Compare traditional regression with regularized regression techniques.
* Improve model reliability through feature selection and multicollinearity reduction.

## Dataset Description

The dataset contains information about Toyota Corolla vehicles, including:

* Vehicle Age
* Mileage (KM Driven)
* Fuel Type
* Horsepower (HP)
* Engine Capacity (CC)
* Number of Doors
* Vehicle Weight
* Quarterly Tax
* Selling Price (Target Variable)

## Methodology

### Data Preprocessing

* Data cleaning and validation
* Handling missing values
* Duplicate record removal
* Outlier treatment using the IQR method

### Exploratory Data Analysis

* Distribution analysis of numerical variables
* Correlation analysis
* Identification of influential features

### Feature Engineering

* One-Hot Encoding for categorical variables
* Feature scaling using StandardScaler

### Feature Selection

* F-Regression based feature ranking
* Selection of statistically significant predictors

### Multicollinearity Analysis

* Variance Inflation Factor (VIF) assessment
* Removal of highly correlated features

## Models Implemented

### Multiple Linear Regression

A baseline regression model developed to establish relationships between independent variables and vehicle price.

### Elastic Net Regression

A regularized regression model combining L1 and L2 penalties to improve generalization and reduce overfitting.

### Ridge Regression

Applied to reduce coefficient variance and improve model stability.

### Lasso Regression

Used for automatic feature selection by shrinking less important coefficients toward zero.

## Results

The models demonstrated strong predictive performance, with Multiple Linear Regression and Elastic Net Regression achieving an R² score of approximately 0.83–0.84. The results indicate that the selected features effectively explain a significant portion of the variation in vehicle prices.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Statsmodels

## Key Learnings

* Multiple Linear Regression Modeling
* Feature Selection Techniques
* Multicollinearity Detection and Reduction
* Regularization Methods (Ridge, Lasso, Elastic Net)
* Model Evaluation and Performance Analysis
* End-to-End Machine Learning Pipeline Development

## Future Enhancements

* Implementation of ensemble learning models such as Random Forest and XGBoost
* Hyperparameter optimization using advanced tuning frameworks
* Deployment through Flask or Streamlit
* Development of an interactive web-based prediction interface

## Conclusion

This project demonstrates the application of statistical and machine learning techniques to predict automobile prices. By combining data preprocessing, feature engineering, and regression modeling, the solution provides a reliable framework for understanding the factors that influence vehicle valuation and generating accurate price predictions.
