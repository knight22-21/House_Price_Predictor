# House Price Prediction
This project aims to predict house prices based on various features using a machine learning model. The dataset has been preprocessed and divided into training and validation sets to evaluate the model's performance. The following sections describe the data processing, model building, and evaluation steps

# Project Report: House Price Prediction
## 1. Introduction
This project focuses on developing a machine learning model to predict house prices based on various features, such as lot size, number of rooms, and neighborhood. The project utilizes regression models to provide accurate predictions, with an emphasis on data preprocessing and feature engineering.

## 2. Objectives
Develop a Price Prediction Model: Build a model to predict house prices based on input features, utilizing regression techniques.
Preprocess and Engineer Features: Clean the dataset and engineer relevant features to enhance model performance.
Evaluate Model Performance: Assess the accuracy and effectiveness of the model through validation metrics.

## 3. Methodology
3.1 Data Collection
The dataset contains information about houses and their features, such as:

Lot size
Number of bedrooms and bathrooms
Square footage
Year built
Neighborhood
This data serves as the foundation for training and evaluating the predictive model.

3.2 Data Preprocessing
Data Cleaning:
Removed unnecessary columns and handled missing values.
Standardized numerical values and handled categorical data.
Feature Engineering:
Created additional features, such as Total_SF, Total_Bathrooms and etc.
Normalized data to improve model performance and prevent biases.
3.3 Model Development
The house price prediction model was developed using the following steps:

Model Selection: Multiple regression algorithms were tested, including Linear Regression, Random Forest, Gradient Boosting, etc.
Training and Validation: The dataset was divided into training and validation sets (X_train, y_train, X_valid, y_valid) for model development and performance evaluation.
Evaluation Metrics: The model was evaluated using Validation RMSE and Cross-Validation RMSE to measure accuracy and consistency.

## 4. Results
The model achieved promising results in predicting house prices, with the best model selected based on validation performance. The final model's accuracy indicates strong predictive capabilities, with error metrics as follows:

Validation RMSE: 0.38605401013102986
Cross-Validation RMSE: 0.4119845961364933
These metrics demonstrate the model's effectiveness in predicting house prices for unseen data.

## 5. Conclusion
The project successfully developed a regression-based house price prediction model. The preprocessing and feature engineering steps significantly improved the model's accuracy, and the selected model is suitable for real-world house price predictions. Future work may involve exploring advanced models or adding more external data sources for improved predictions.

## 6. Model used
The final model used is Lasso regression.

## 7. References
Dataset Source: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques Available on Kaggle

