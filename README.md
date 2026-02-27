# AI_ML-Internship-Tasks
## AI & ML Internship Projects

This repository contains my AI & ML internship tasks, demonstrating data analysis, predictive modeling, and machine learning applications on real-world datasets. The projects cover classification, regression, and stock/price prediction tasks using Python, Pandas, scikit-learn, and visualization libraries.

# Overview of Projects

The projects in this repository include:

Iris Dataset Analysis – classification of iris flower species.

Apple Stock Price Prediction – predicting stock prices using historical data.

House Price Prediction – predicting house prices using property features.

Each project involves data exploration, preprocessing, modeling, evaluation, and visualization.

# Datasets

The datasets used are stored in the datasets/ folder:

iris.csv – Iris dataset with 150 samples of three species (Setosa, Versicolor, Virginica) and features: sepal length, sepal width, petal length, petal width.

apple_stock.csv – Apple Inc. historical stock prices with columns: Date, Open, High, Low, Close, Adj Close, Volume.

housing.csv – Housing dataset including price, area, bedrooms, bathrooms, stories, mainroad, guestroom, basement, hotwaterheating, airconditioning, parking, prefarea, and furnishingstatus.

# Workflow Across Projects
## 1. Data Loading and Exploration

Loaded datasets using Pandas.

Checked for missing values and data types.

Generated summary statistics.

Visualized distributions and relationships using matplotlib and seaborn.

## 2. Data Preprocessing

Handled categorical variables using one-hot encoding.

Filled missing or infinite values with median values.

Converted date columns to datetime for time-series analysis.

Split datasets into features (X) and target (y).

## 3. Modeling

Applied classification models on the Iris dataset: Logistic Regression, Decision Tree, KNN.

Applied regression models on Apple stock and housing data: Linear Regression, Random Forest Regressor.

Trained models on 80% of data and tested on 20%.

## 4. Evaluation

Used accuracy and confusion matrix for classification tasks.

Used Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE) for regression tasks.

## 5. Visualization

Visualized relationships between features (pairplots, histograms).

Plotted actual vs predicted values (scatter plots, line plots).

Observed feature importance and trends for predictions.

# Key Insights

Iris dataset: Setosa species is easily separable using petal length and width. Logistic Regression performs well.

Apple stock: Gradient Boosting and Random Forest improve prediction accuracy compared to Linear Regression. Trends are visible in long-term stock charts.

Housing dataset: Features like area, bedrooms, and furnishing status strongly influence house prices. Linear Regression provides reasonable predictions.

## How to Run

## Clone the repository:

git clone https://github.com/somiaiqbal/AI_ML-Internship-Tasks.git

## Open the Jupyter notebooks for each project:

### Task1_Iris_Analysis.ipynb

### Task_Stock_Prediction.ipynb

### Task_HousePrice_Prediction.ipynb

Run all cells sequentially.

## Repository Structure
AI_ML-Internship-Tasks/
    Task1_Iris_Analysis.ipynb
    Task_Stock_Prediction.ipynb
    Task_HousePrice_Prediction.ipynb
 datasets/
     iris.csv
     appl.csv
     house price,csv
README.md
