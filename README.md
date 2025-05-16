# Weather Forecasting Project

## Project Overview

This project focuses on forecasting temperature using weather data through a comprehensive machine learning pipeline. It covers:

- Data preprocessing and cleaning  
- Exploratory data analysis  
- Building regression models: Multiple Linear Regression, Decision Tree, Random Forest, and XGBoost  
- Hyperparameter tuning on XGBoost for improved accuracy  
- Model evaluation and comparison using MAE, MSE, RMSE, and R² scores  
- Feature importance analysis to select the most impactful features  
- Preparing an updated dataset for time series forecasting  
- Multi-step (7-day) temperature forecasting using the tuned XGBoost model  

---

## Dataset

The dataset consists of weather-related features collected over time, including temperature and other relevant meteorological variables.

---

## Project Structure

- `data/` — Original and processed datasets  
- `notebooks/` — Jupyter notebooks for EDA, modeling, and evaluation  
- `models/` — Saved machine learning models  
 

---

## Key Steps

### 1. Data Preprocessing and Cleaning
- Handling missing values  
- Dropping duplicates  
- Encoding categorical features (One-hot encoding)  
- Normalization and scaling (Min-Max scaling)  
- Parsing datetime columns and creating lag features  

### 2. Modeling
- Training four regression models:  
  - Multiple Linear Regression  
  - Decision Tree Regression  
  - Random Forest Regression  
  - XGBoost Regression  
- Evaluating models with Mean Absolute Error (MAE), Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R² score  
- Hyperparameter tuning on XGBoost for better performance  

### 3. Feature Importance
- Extracting feature importance from the tuned XGBoost model  
- Selecting best features for improved model accuracy  

### 4. Time Series Forecasting
- Preparing data for multi-step forecasting  
- Implementing 7-day temperature forecasting using XGBoost  
- Saving updated datasets with selected features for future use  


