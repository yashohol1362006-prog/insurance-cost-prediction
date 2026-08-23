# insurance-cost-prediction
Machine learning project to analyze and predict medical insurance charges using EDA, feature engineering, statistical analysis, and Linear Regression.
# Insurance Cost Prediction

## Overview

This project analyzes medical insurance data and builds a machine learning model to predict insurance charges based on demographic and health-related features.

## Dataset

The dataset contains 1,338 records with the following features:

* Age
* Sex
* BMI
* Number of children
* Smoker status
* Region
* Insurance charges

## Project Workflow

### 1. Exploratory Data Analysis

* Loaded the dataset using Pandas
* Checked dataset shape and data types
* Examined statistical summaries
* Checked for missing values
* Visualized feature distributions

### 2. Feature Engineering

* Converted categorical variables into numerical features
* Created BMI categories
* Applied one-hot encoding
* Standardized numerical features such as age, BMI, and number of children

### 3. Feature Analysis

* Calculated Pearson correlation between features and insurance charges
* Used Chi-square testing to examine categorical features
* Compared feature relationships with the target variable

### 4. Machine Learning

Used **Linear Regression** to predict insurance charges.

The dataset was divided into training and testing sets using an 80/20 split.

### 5. Model Evaluation

The model was evaluated using:

* R² Score
* Adjusted R² Score

The notebook obtained an R² score of approximately **0.798** on the test set.

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* SciPy
* Scikit-learn

## Key Learning Outcomes

Through this project, I practiced:

* Exploratory Data Analysis
* Data preprocessing
* Feature engineering
* Categorical encoding
* Feature scaling
* Statistical feature analysis
* Train-test splitting
* Linear Regression
* Model evaluation
