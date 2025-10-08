# Sales-Forecasting-Description

Project Goal
This project tackles Time Series Forecasting to predict future weekly sales for a major retailer (based on the Walmart Sales Forecast dataset). The main objective was to build a machine learning model that accurately accounts for seasonal patterns, trends, and time-based dependencies.

Key Concepts Covered
Time Series Analysis: Handling data indexed by time.

Feature Engineering: Creating predictor variables from the Date column (e.g., Month, Weekday).

Lag Features: Using previous week's sales (e.g., Sales_Lag_1) as the primary predictor.

Regression Modeling: Using machine learning to predict a continuous sales value.

Methodology & Results
Data Preparation: Aggregated weekly sales data and performed time-aware splitting (training on past data only).

Core Modeling: Used Linear Regression as a performance baseline.

Advanced Solution (Bonus): Implemented the powerful XGBoost Regressor to significantly improve prediction accuracy by better capturing non-linear relationships and holiday sales spikes.

Evaluation: Forecast accuracy was measured using R-squared (R 
2
 ), RMSE, and MAE.


🛠️ Technologies
Python

Pandas (Data Manipulation)

Scikit-learn (Metrics & Baseline Model)

XGBoost (Advanced Forecasting Model)

Matplotlib (Visualization of Actual vs. Predicted Sales)
