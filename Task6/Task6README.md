## 🏠 House Price Prediction
## Overview

This project focuses on predicting house prices using regression techniques. The dataset contains housing features such as square footage, number of bedrooms, and location. The goal is to build machine learning models that estimate house prices based on these features.

## Task Objective

Understand the structure of the housing dataset.

Perform data preprocessing.

Apply regression models to predict house prices.

Evaluate model performance using MAE and RMSE.

Visualize actual vs predicted prices.

## Dataset

The dataset contains the following features:

sqft_living: Total living area in square feet.

bedrooms: Number of bedrooms in the house.

statezip (or location column): Location of the house.

price: Target variable (house price).

## Steps Performed in Task
## Step 1: Load Dataset

Loaded the CSV file using Pandas.

Displayed the first few rows to understand structure.

## Step 2: Data Preprocessing

Selected relevant features (size, bedrooms, location).

Checked and handled missing values.

Applied One-Hot Encoding to convert categorical location feature.

Split dataset into features (X) and target (y).

Divided data into training (80%) and testing (20%) sets.

Applied feature scaling using StandardScaler.

## Step 3: Modeling

Two regression models were trained:

Linear Regression

Assumes linear relationship between features and price.

Ensemble model that builds multiple decision trees sequentially.

Captures non-linear relationships in housing data.

## Step 4: Model Evaluation

Models were evaluated using:

Mean Absolute Error (MAE)
Measures average prediction error.

Root Mean Squared Error (RMSE)
Penalizes larger errors more strongly.

Lower MAE and RMSE indicate better performance.

## Step 5: Visualization

Created scatter plot of actual vs predicted prices.

If points lie close to the diagonal line, predictions are accurate.

## Results & Insights

Both Linear Regression and Gradient Boosting were tested.

Linear Regression showed slightly lower MAE and RMSE.

High RMSE suggests presence of outliers or limited feature selection.

House price prediction improves when more features are included (e.g., bathrooms, year built, condition).

## How to Run

Clone the repository.

Open the Jupyter Notebook (e.g., Task6_House_Price_Prediction.ipynb).

Ensure the dataset CSV file is in the same directory.

Run all cells in order.

## Author

Somia Iqbal

AI / ML Student

GitHub: https://github.com/somiaiqbal
