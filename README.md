# OIBSIP_domain_task_no_5
## Problem Statement :
Sales forecasting is crucial for inventory planning, marketing strategies, and resource allocation. The goal is to develop a machine learning model that can predict future sales based on historical sales data, promotions, store information, and other influencing factors.

## Objective :
To build a predictive model that accurately estimates product sales using past trends and available features. This involves end-to-end steps: data analysis, feature engineering, model building, evaluation, and selection of the best-performing regression model.

## Steps Performed :
1. Data Collection & Loading :
Imported the dataset (CSV format) with historical sales data.
2. Exploratory Data Analysis (EDA) :
Visualized sales trends across products, stores, and dates using:
Time-series plots
Bar charts
Heatmaps and correlation matrices
3. Data Preprocessing :
Handled missing values and duplicates
Converted date formats and created new features (e.g., Month, Year, Day)
4. Encoded categorical variables like Store ID, Product ID :
Performed feature scaling where required
5. Model Training :
Trained multiple regression models:

Linear Regression
Decision Tree Regressor
Support Vector Regressor
Random Forest Regressor
XGBoost Regressor
6. Model Evaluation :
Compared models using:

R² Score
RMSE
MAE
## Tools and Technologies Used :
Programming Language: Python
Development Environment: Jupyter Notebook / Google Colab
Libraries & Frameworks:
pandas, numpy – for data handling
matplotlib, seaborn, plotly – for visualization
scikit-learn – model building, preprocessing, and evaluation
xgboost – gradient boosting algorithm

## Outcome :
Successfully developed a machine learning model that predicts future sales with high accuracy.
Identified major factors affecting sales such as promotions, holidays, and seasonal trends.
Achieved R² score above 90% using XGBoost.
Enhanced understanding of time series patterns, regression modeling, and evaluation techniques.

## Conclusion :
The sales prediction model demonstrates the effectiveness of machine learning in forecasting future performance based on historical data. By identifying key trends and patterns, businesses can make better decisions in inventory management, marketing, and budgeting.
