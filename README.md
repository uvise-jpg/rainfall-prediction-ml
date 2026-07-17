# Rainfall Prediction Using Machine Learning

## Overview

This project predicts rainfall occurrence using weather-related parameters and Machine Learning techniques. The model is trained on historical weather data and can determine whether rainfall is likely to occur based on atmospheric conditions.

The project covers the complete Machine Learning workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, hyperparameter tuning, evaluation, and prediction.

## Features

* Data cleaning and preprocessing
* Missing value handling
* Exploratory Data Analysis (EDA)
* Correlation analysis and data visualization
* Class imbalance handling through downsampling
* Random Forest Classifier implementation
* Hyperparameter tuning using GridSearchCV
* Cross-validation for model evaluation
* Rainfall prediction on new weather data
* Model serialization using Pickle

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Pickle

## Dataset Features

The model uses the following weather parameters:

* Pressure
* Dew Point
* Humidity
* Cloud Cover
* Sunshine
* Wind Direction
* Wind Speed

Target Variable:

* Rainfall (Yes/No)

## Machine Learning Workflow

### Data Preprocessing

* Removed unnecessary columns
* Handled missing values
* Converted categorical rainfall values into numerical format
* Balanced the dataset using downsampling

### Exploratory Data Analysis

* Distribution plots
* Rainfall frequency analysis
* Correlation heatmap
* Outlier detection using boxplots

### Model Training

* Random Forest Classifier
* Hyperparameter optimization using GridSearchCV
* 5-Fold Cross Validation

### Model Evaluation

* Accuracy Score
* Confusion Matrix
* Classification Report
* Cross-Validation Performance

## Prediction Example

Input Weather Conditions:

* Pressure: 1015.9
* Dew Point: 19.9
* Humidity: 95
* Cloud Cover: 81
* Sunshine: 0.0
* Wind Direction: 40.0
* Wind Speed: 13.7

Output:

* Rainfall
* No Rainfall

## Project Structure

```text
rainfall-prediction-ml/
│
├── Rainfall_Prediction.ipynb
├── rainfall_prediction_model.pkl
├── README.md
└── dataset.csv
```

## Future Improvements

* Implement SMOTE for class balancing
* Compare multiple Machine Learning algorithms
* Apply PCA for dimensionality reduction
* Deploy as a web application
* Build an interactive prediction dashboard
