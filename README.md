# Prediction of Sea Surface Temperature Using Atmospheric Features

## Overview
This project focuses on predicting Sea Surface Temperature (SST) using atmospheric features. The study aims to explore the predictive capabilities of various atmospheric variables in forecasting SST variations, contributing to the advancement of climate modeling and predictive analytics.

## Introduction
The idea for this project arose from the need to forecast devastating events such as heavy rainfalls, destructive floods, and droughts caused by rising temperatures. Predicting parameters like SST is crucial for explaining and potentially mitigating such events. El Niño, a significant climate phenomenon, is known to trigger natural disasters. This study examines the relationship between atmospheric conditions and SST fluctuations, particularly during El Niño events.

## Data Cleaning or Pre-processing
The dataset used for this project is the El Niño dataset from Kaggle, containing over one hundred thousand observations with 12 features. Initial exploration revealed many missing values and inappropriate data types for some features. Data pre-processing was performed to ensure the quality and accuracy of the model. This process enhances the interpretability of results and saves time.

## Exploratory Data Analysis (EDA)
Key questions addressed during EDA include:
1. How do the variables relate to each other?
2. Which variables have a greater effect on climate variations?

EDA involves understanding the data and preparing it for modeling. It includes feature engineering, which involves creating or transforming features to improve model performance, and feature selection, which identifies the most relevant features from the dataset. The main features of interest include Zonal Winds, Meridional Winds, Humidity, Air Temperature, and Sea Surface Temperature. The target variable, Sea Surface Temperature, indicates changes in the El Niño effect.

## Model Training and Prediction
The dataset was split into training and test sets to evaluate the performance of machine learning models. The following regression algorithms were used to predict SST:
- Linear Regression
- Decision Tree Regression
- Random Forest Regression
- k-Nearest Neighbor Regression

Each algorithm has unique advantages for predicting SST, a complex and dynamic variable.

## Result Interpretation
Among the algorithms used, the Random Forest method effectively predicted SST based on atmospheric variables. It achieved a high R-squared value and the lowest Mean Squared Error, demonstrating superior performance in capturing the relationships between atmospheric conditions and SST dynamics. The Random Forest model explained over 91% of the variation in SST, indicating its exceptional accuracy.

## Conclusion
The study investigated the prediction of SST using atmospheric variables and found that the Random Forest method outperformed other algorithms, achieving a remarkable R-squared value and the lowest Mean Squared Error. This indicates the model's exceptional ability to explain SST variation with high accuracy. Future research could explore additional predictors and refine modeling techniques to further enhance the accuracy and robustness of SST predictions, contributing to a better understanding of climate dynamics and environmental forecasting.

Thank you for your attention.
