# Car Price Prediction Using Machine Learning

## Overview

This project aims to predict the selling price of used cars using Machine Learning techniques. The model analyzes various factors such as car age, fuel type, transmission type, kilometers driven, and ownership details to estimate the resale value of a vehicle.

## Objective

To build and evaluate regression models that can accurately predict the selling price of a used car based on its features.

## Dataset

The dataset used in this project is the **Vehicle Dataset from CarDekho**, which contains information about used cars, including:

1. name           
2. year            
3. selling_price   
4. km_driven       
5. fuel           
6. seller_type    
7. transmission
8. owner     

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn

## Project Workflow

### 1. Data Collection

* Loaded the CarDekho dataset.
* Inspected dataset structure and data types.

### 2. Data Cleaning

* Checked for missing values.
* Removed duplicate records.
* Standardized categorical values for consistency.

### 3. Feature Engineering

* Created a new feature: **Car Age** from the manufacturing year.
* Extracted **Brand Name** from the car name column.

### 4. Exploratory Data Analysis (EDA)

* Distribution of Selling Prices
* Price vs Fuel Type Analysis
* Price vs Car Age Analysis
* Correlation Analysis

### 5. Data Preprocessing

* Encoded categorical variables using One-Hot Encoding.
* Prepared feature and target variables.
* Split data into training and testing sets.

### 6. Model Building

Two regression models were trained:

1. Linear Regression
2. Random Forest Regressor

### 7. Model Evaluation

Models were evaluated using:

* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* R² Score

### 8. Feature Importance Analysis

Feature importance was extracted from the best-performing model to identify the most influential factors affecting car prices.

## Results

Random Forest Regressor achieved better performance compared to Linear Regression and was selected as the final model for car price prediction.

## Key Insights

* Car age has a significant impact on resale value.
* Fuel type influences the selling price.
* Newer cars generally have higher resale values.
* Random Forest captured complex relationships in the data more effectively than Linear Regression.

## Conclusion

This project demonstrates the application of Machine Learning regression techniques to predict used car prices. Through data cleaning, feature engineering, visualization, and model comparison, an effective predictive model was developed for estimating vehicle resale values.

