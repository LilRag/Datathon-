# Datathon Data Analysis Project
## Overview
This repository contains the analysis and visualization of a  dataset as part of a datathon challenge. The project focuses on data cleaning, exploratory data analysis (EDA), and deriving meaningful insights through various statistical methods and visualizations

## Dataset
Size: 1000 rows
Format: CSV file
Source: heart_disease.csv -> https://www.kaggle.com/datasets/volodymyrgavrysh/heart-disease/data

## Data Cleaning Process

### Missing Value Treatment
Identified and handled NULL values
Removed duplicate entries
### Handling Outliers 
Identified the IQR range and removed the outliers. 

## Analysis Performed

### Exploratory Data Analysis

  Statistical summary of numerical columns
  Distribution analysis
  Correlation studies
  Outlier detection
  Predictive Modeling

  
### Statistical Analysis

  Hypothesis Testing
  
  Conducted independent t-test to compare cholesterol levels between heart disease and non-heart disease groups
  Null Hypothesis (H₀): No significant difference in cholesterol levels between groups
  Alternative Hypothesis (H₁): Significant difference exists in cholesterol levels between groups
  Statistical significance level (α) = 0.05

### Linear Regression Analysis

  Target Variable: Cholesterol levels
  Features:
  
  Age
  Resting Blood Pressure (trestbps)
  Maximum Heart Rate (thalch)
  ST depression induced by exercise (oldpeak)
  Number of major vessels (ca)
  Diagnosis of heart disease (num)
  
  
  Model Evaluation Metrics:
  
  Root Mean Square Error (RMSE)
  Mean Square Error (MSE)
  R-squared (R²)
  
  
  Model validation using train-test split

### Visualizations

  Histograms for numerical variables
  Box plots for outlier analysis
  Correlation heatmaps
  Scatter plots for regression analysis
  Residual plots for model diagnostics
  Actual vs Predicted value plots
  Distribution plots comparing cholesterol levels between group
  


