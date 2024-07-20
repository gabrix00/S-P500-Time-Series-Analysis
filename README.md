#Project Overview
This project focuses on time series data analysis and forecasting, specifically aiming to:

## Assess if a process is stationary or not and apply transformations to achieve stationarity.
* Identify and evaluate the presence of trend and seasonality in the data.
* Identify appropriate models for forecasting.
* Compare the performance of traditional statistical models and modern machine learning models for one-day ahead predictions.
## Models Evaluated
* ARIMA (AutoRegressive Integrated Moving Average): A traditional statistical model used for time series forecasting.
* XGBoost (Extreme Gradient Boosting): A powerful machine learning model that can be used for time series forecasting.
* Persistence Model: A simple baseline model that assumes tomorrow's value will be the same as today's.
##Steps and Methodology
Data Exploration and Preprocessing:
* Load and visualize the time series data.
* Assess stationarity using tests like the Augmented Dickey-Fuller test.
* Apply transformations if necessary (e.g., differencing) to achieve stationarity.
* Decompose the time series to analyze trend and seasonality.
## Model Identification and Training:
* Identify appropriate parameters for the ARIMA model.
* Train the XGBoost model with relevant features.
* Implement the persistence model.
##Model Evaluation:
* Make one-day ahead predictions using each model.
* valuate model performance using metrics such as Mean Absolute Error (MAE) and Root Mean Squared Error (RMSE).
