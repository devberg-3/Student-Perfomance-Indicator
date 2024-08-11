# Student Performance Predictor

## Overview

This project aims to predict student performance based on various features using machine learning techniques. The pipeline includes data ingestion, preprocessing, model training, and prediction. The primary goal is to create a robust model that can accurately assess student performance indicators.

## Components

1. **Data Ingestion**: Handles reading and splitting the dataset into training and testing sets.
2. **Data Transformation**: Applies preprocessing steps like scaling numerical features and encoding categorical variables.
3. **Model Training**: Trains multiple regression models (e.g., Random Forest, Gradient Boosting, XGBoost) and selects the best-performing model based on evaluation metrics.
4. **Prediction Pipeline**: Loads the trained model and preprocessing pipeline to make predictions on new data.
5. **Custom Data Class**: Provides a way to input new data and convert it into the required format for predictions.

## Requirements

- Python 3.8+
- Pandas
- NumPy
- Scikit-learn
- CatBoost
- XGBoost
- Other dependencies (see `requirements.txt`)

