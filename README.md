# ML Class Practice - Logistic and Linear Regression Exercises

Author: Papagrigoriou Vasileios Savvas (vpapagr@csd.auth.gr)

## Introduction
This document outlines the exercises conducted in the ML class focusing on Logistic and Linear Regression. The exercises involve the analysis of a diabetes dataset using different regression techniques to understand and predict diabetes and blood pressure levels.

## Exercise 1: Logistic Regression

### Overview
Utilize logistic regression models to predict the outcome of diabetes based on various health metrics.

### Implementation Steps
1. **Import Libraries**: Import necessary libraries like pandas, sklearn, and matplotlib.
2. **Load Dataset**: Load the diabetes dataset into a DataFrame.
3. **Prepare Data**: Convert DataFrame to input (X) and target (y) arrays.
4. **Split Dataset**: Split the dataset into training and testing sets.
5. **Create Models**: Create Logistic Regression models with different penalties (None, L1, L2).
6. **Train Models**: Fit the models to the training data.
7. **Compute Predictions**: Make predictions on the test data.
8. **Evaluate Models**: Calculate the accuracy of each model and discuss the implications of their predictions.

## Exercise 2: Linear Regression

### Overview
Apply linear regression techniques to predict blood pressure based on age, BMI, and pregnancy count.

### Steps
1. **Reset Environment**: Clear the environment to manage variable space.
2. **Import Libraries and Models**: Import necessary libraries and linear regression models.
3. **Select Features**: Define input and target features for the regression task.
4. **Load and Split Dataset**: Load the dataset and split it into training and testing sets.
5. **Create Models**: Initialize different linear regression models including SGDRegressor.
6. **Fit Models**: Train the models on the training data.
7. **Make Predictions**: Use the models to predict blood pressure in the test data.
8. **Evaluate Models**: Calculate mean absolute error (MAE) for each model.
9. **Analyze Results**: Compute mean and variance differences between train and test sets, and plot histograms to visualize the distribution.
