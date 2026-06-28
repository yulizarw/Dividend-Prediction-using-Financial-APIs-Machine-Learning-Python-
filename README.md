# Dividend-Prediction-using-Financial-APIs-Machine-Learning-Python-
Developed an end-to-end machine learning pipeline that integrates IMF and Alpha Vantage APIs to analyze economic indicators, perform exploratory data analysis, feature engineering, and predict corporate dividend estimates using regression models.
# Dividend Prediction using Financial APIs & Machine Learning

A Python-based end-to-end data science project that combines macroeconomic indicators from the IMF and financial market data from Alpha Vantage to analyze and predict corporate dividend estimates (EPS).

---

## Overview

This project demonstrates a complete machine learning workflow, starting from data collection through public APIs, data preprocessing, exploratory data analysis (EDA), feature engineering, feature selection, model training, evaluation, and prediction.

The objective is to understand how financial reporting dates and market information influence dividend estimates.

---

## Features

- Retrieve macroeconomic data from IMF API
- Retrieve Earnings Calendar from Alpha Vantage API
- Financial data preprocessing
- Missing value handling
- Outlier analysis
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Scaling comparison
- Feature Selection (F-Test & Mutual Information)
- Regression Model Development
- Model Evaluation
- Manual prediction (Inference)

---

## Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Plotly
- Requests API

---

## Data Sources

### IMF API

Macroeconomic indicators used to understand Indonesia's economic conditions.

### Alpha Vantage API

Financial market data including:

- Earnings Calendar
- Earnings Per Share (EPS)
- Report Date
- Fiscal Date Ending
- Currency
- Company Information

---

## Machine Learning Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis
4. Feature Engineering
5. Feature Scaling Comparison
6. Feature Selection
7. Model Development
8. Model Evaluation
9. Model Inference

---

## Exploratory Data Analysis

The project includes:

- Distribution analysis
- Missing value analysis
- Outlier detection
- Time-series visualization
- Currency comparison
- Correlation analysis
- Statistical summaries

---

## Feature Engineering

Several preprocessing techniques were evaluated, including:

- StandardScaler
- MinMaxScaler
- RobustScaler
- MaxAbsScaler

Feature importance was analyzed using:

- ANOVA F-Test
- Mutual Information

---

## Machine Learning Models

The project explores regression models to predict dividend estimates using financial reporting information and engineered features.

---

## Example Outputs

- Dividend estimate prediction
- Feature importance ranking
- Distribution plots
- Correlation analysis
- Time-series visualization
- Model evaluation metrics

---

## Learning Objectives

This project was developed to practice:

- API Integration
- Financial Data Analytics
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Feature Selection
- Machine Learning Regression
- Data Visualization
- Predictive Analytics

---

## Future Improvements

- XGBoost & LightGBM models
- Hyperparameter tuning
- Time-series forecasting
- SHAP Explainable AI
- Streamlit Dashboard
- Portfolio recommendation system
- Automated data pipeline

---

## Project Structure

```
├── notebooks/
├── data/
├── figures/
├── models/
├── output/
└── README.md
```

---

## Disclaimer

This project is intended for educational purposes and demonstrates the implementation of financial data analytics and machine learning techniques. It should not be considered financial or investment advice.
