# 🕒 Multivariate Time Series Sales Forecasting

This project focuses on building and evaluating a multivariate time series model to predict daily sales for multiple products across different cities. The aim is to provide accurate sales forecasts for the next 10 days using historical data and engineered time-dependent features.

---

## 📊 Overview

This notebook tackles a classic time series forecasting task involving:
- Multivariate time series data grouped by `Product_ID` and `City_Code`.
- Data preprocessing including log transformation, decomposition, and outlier handling.
- Unified modeling across grouped time series using feature engineering.
- Forecasting using machine learning models with evaluation metrics.

---

## 🔧 Features & Techniques Used

- ✅ **Data Cleaning**: Null handling, grouping, resampling  
- 📉 **Log Transformation**: To stabilize variance  
- 📈 **Trend & Seasonality Decomposition**: Using STL  
- 🚨 **Outlier Detection**: Visual + IQR-based methods  
- 🧠 **Feature Engineering**: Lag features, time-based variables  
- 📦 **Modeling**: Applied single regression model across all time series groups  
- 📏 **Evaluation**: RMSE, MAE, and prediction plots
