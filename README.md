# Electricity Demand Forecasting Using Machine Learning: A Time-Series Approach with Feature Engineering and Model Optimisation
## Project Overview
This project focuses on forecasting electricity demand using historical data from 2009 to 2024. It explores time-series analysis, feature engineering, and the optimization of machine learning models to predict future energy consumption patterns.

## Methodology
The project follows a structured data science workflow:
1. **Data Preprocessing**: Handling missing values, formatting datetime indices, and cleaning the national demand dataset.
2. **Exploratory Data Analysis (EDA)**: Visualizing trends, seasonality, and the impact of holidays on electricity consumption.
3. **Feature Engineering**: Creating lag features, rolling windows, and extracting temporal components (hour, day of week, month).
4. **Model Selection**: Implementing and comparing:
   - Linear Regression
   - Random Forest Regressor
   - XGBoost Regressor
5. **Model Optimization**: Using `TimeSeriesSplit` and `GridSearchCV` for hyperparameter tuning to minimize RMSE and MAE.

## Requirements
To run the code, you will need the following Python libraries:
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `xgboost`

## Academic Integrity Statement
All code presented in the final version and the development history is my own work, except where explicitly cited through comments. Standard library functions and documentation from Scikit-Learn and XGBoost were used as references for implementation.
README.md
Displaying README.md.
