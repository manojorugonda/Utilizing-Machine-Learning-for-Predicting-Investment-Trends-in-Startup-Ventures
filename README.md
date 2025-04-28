# Utilizing Machine Learning for Predicting Investment Trends in Startup Ventures

## Overview

This project has been done to employ a predictive approach by applying machine learning to predict future investment trends in startups to get more profit.

## Features

1. **Data Processing:**
   - Reading Data from the directory.
   - Cleaning missing values from data through missing value cleaning technique.

2. **Exploratory Data Analysis (EDA):**
   - The analysis has been done on data feature to explore insights.
   - The outcomes of the analyses have been presented through graphs.

3. **Feature Preprocessing:**
   - Categorical features have been transformed to numerical ones.
   - Applying PCA to detect outliers from data features
   - Applying Data Normalization technique through MinMaxScaler to reduced outliers from data by normalizing features.
   - The features from dataset has been selected using ensemble technique where Random Forest has been used.

4. **Model Optimization and Model Preparation:**
   - The GridSearch method with 5-Fold Cross Validation has been employed to the chosen models to optimize the parameter settings.
   - The tuned models have been prepared using the optimized parameters.

5. **Investment Trends Prediction:**
   - The optimized models have been trained and tested.
   - The prediction has been done for Investment Trends using the optimized models.
   - The performances of the models have been compared using regression metrics Prediction Error(Train R2-Test R2), MSE, MAPE, Variance Error etc.

6. **Result Visualization:**
   - The performances of the models have been visualized through graphs using bar charts.

## Requirements

The project requires Python 3.9 or above and the following Python libraries:

- `warnings`
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `sklearn`

Install dependencies using the following command:
```
pip install numpy pandas matplotlib seaborn scikit-learn



```python

```

