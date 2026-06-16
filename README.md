# Project Summary
Analyzed air quality data using EDA and machine learning to identify pollution patterns and predict PM2.5 levels.

# Air Quality Prediction

## Project Description

Analyzed air quality data using exploratory data analysis (EDA) and machine learning techniques to identify pollution patterns and predict PM2.5 levels.

## Overview

Air pollution is a major environmental and public health concern. This project explores the relationship between meteorological factors and PM2.5 concentration levels using data analysis and machine learning techniques. The goal was to understand key pollution drivers and evaluate predictive models for air quality forecasting.

## Objectives

* Analyze environmental factors affecting PM2.5 levels.
* Perform data cleaning and preprocessing.
* Visualize trends and relationships within the dataset.
* Identify important predictors through correlation analysis.
* Compare machine learning models for PM2.5 prediction.

## Dataset Features

The dataset contains hourly environmental readings collected from monitoring stations, including:

* Temperature
* Humidity
* Atmospheric Pressure
* Wind Speed
* PM2.5 Concentration (Target Variable)

## Data Preprocessing

The following preprocessing techniques were applied:

* Handling missing values using median imputation.
* Outlier treatment through percentile-based capping.
* Data cleaning and preparation.
* Feature correlation analysis.

## Exploratory Data Analysis

Several visualizations were used to understand the data:

* Correlation Heatmaps
* Scatter Plots
* Distribution Analysis
* Relationship Analysis between weather variables and PM2.5

### Key Insights

* Higher wind speed was associated with lower PM2.5 levels.
* Humidity showed a positive relationship with pollution concentration.
* Temperature had a moderate influence on pollutant dispersion.
* Atmospheric pressure contributed less to prediction accuracy.

## Machine Learning Models

### Linear Regression

* Simple and interpretable baseline model.
* Effective for linear relationships.

### Random Forest Regressor

* Captures non-linear relationships.
* Handles complex feature interactions.
* More robust to noise and outliers.

## Model Performance

| Model             | R² Score |
| ----------------- | -------- |
| Linear Regression | ~0.62    |
| Random Forest     | ~0.89    |

Random Forest significantly outperformed Linear Regression, demonstrating stronger predictive capability for PM2.5 forecasting.

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

## Conclusion

This project demonstrates how environmental and weather-related factors can be leveraged to predict air quality levels. Through data preprocessing, visualization, and machine learning, meaningful insights were extracted and accurate PM2.5 predictions were achieved using Random Forest models.
