## 📈 Apple Stock Price Prediction
## Overview

This project analyzes historical stock price data of Apple Inc. (AAPL) and builds a machine learning model to predict future stock prices based on past market trends.

The dataset includes daily stock market information such as:

Open price

High price

Low price

Close price

Volume

## Task Objective

Understand stock market time-series data

Perform exploratory data analysis (EDA)

Visualize stock price trends

Apply regression models to predict closing price

Evaluate model performance

## Dataset

The dataset contains historical stock prices of Apple with the following columns:

Date: Trading date

Open: Opening price

High: Highest price of the day

Low: Lowest price of the day

Close: Closing price

Adj Close: Adjusted closing price

Volume: Number of shares traded

## Steps Performed in Task
## Step 1: Load Dataset

Loaded CSV file using Pandas

Converted Date column to datetime format

Set Date as index

## Step 2: Explore Dataset

Checked for missing values

Displayed summary statistics

Visualized stock price trends over time

## Step 3: Data Preprocessing

Selected relevant features (Open, High, Low, Volume)

Target variable: Close price

Split dataset into training and testing sets

Applied feature scaling (if required)

## Step 4: Modeling

Trained regression models such as:

Linear Regression

Random Forest Regressor

Gradient Boosting Regressor

## Step 5: Evaluation

Model performance evaluated using:

Mean Absolute Error (MAE)

Root Mean Squared Error (RMSE)

## Visualization:

Actual vs Predicted price graph

Line plot of stock trends

## Results & Insights

The model successfully learned stock price patterns.

Linear Regression provided baseline performance.

Ensemble models improved prediction accuracy.

Stock prices show clear upward and downward trends over time.

## How to Run

Clone the repository

Open the Jupyter Notebook Task_Stock_Prediction.ipynb

Run all cells in order

## Author

Somia Iqbal

GitHub: https://github.com/somiaiqbal/AI_ML-Internship-Tasks
