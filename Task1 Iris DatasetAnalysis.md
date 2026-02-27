# Iris Dataset Analysis

## Overview
This project analyzes the famous **Iris dataset**. The dataset contains 150 samples of iris flowers from three species (Setosa, Versicolor, Virginica) and includes four features: sepal length, sepal width, petal length, and petal width.  

## Task Objective
- Understand the dataset structure.
- Perform exploratory data analysis (EDA).
- Apply classification models to predict species.
- Visualize results for insights.

## Dataset
The dataset contains the following columns:
- `sepal_length`: Length of the sepal (cm)
- `sepal_width`: Width of the sepal (cm)
- `petal_length`: Length of the petal (cm)
- `petal_width`: Width of the petal (cm)
- `species`: Iris species (Setosa, Versicolor, Virginica)

## Steps Performed in Task

### Step 1: Load Dataset
- Loaded the CSV file using Pandas.
- Displayed first few rows to understand structure.

### Step 2: Explore Dataset
- Checked for null/missing values.
- Summarized basic statistics.
- Visualized feature distributions.

### Step 3: Data Preprocessing
- Converted categorical labels to numeric encoding if needed.
- Split the dataset into features (X) and target (y).

### Step 4: Modeling
- Trained classification models such as:
  - Logistic Regression
  - Decision Tree Classifier
  - K-Nearest Neighbors (KNN)
- Evaluated performance using accuracy and confusion matrix.

### Step 5: Visualization
- Pairplots and histograms for feature relationships.
- Confusion matrix visualization.
- Observed how features separate different iris species.

## Results & Insights
- Iris Setosa is easily separable from others using petal length and width.
- Logistic Regression performed well with high accuracy.
- Decision Trees and KNN also showed strong classification performance.

## How to Run
1. Clone the repository.
2. Open the Jupyter Notebook `Task1_Iris_Analysis.ipynb`.
3. Run the cells in order.

## Author
- **Somia Iqbal**
- GitHub: [https://github.com/somiaiqbal/AI_ML-Internship-Tasks]
