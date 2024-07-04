## Torrent-Power-Stock-Price-Prediction-with-SARIMA-and-ARIMA
This project investigates the potential of statistical time series forecasting models for predicting future closing prices of TorrentPower stock. 
It employs two widely used techniques: Seasonal Autoregressive Integrated Moving Average (SARIMA) and Autoregressive Integrated Moving Average (ARIMA).

Core functionalities:

# Data Acquisition and Preprocessing: 
Historical closing price data of TorrentPower stock will be obtained and meticulously cleaned. Preprocessing steps like handling missing values, identifying outliers, and potentially transforming the data (e.g., differencing) might be necessary.
# Exploratory Data Analysis (EDA):
Visualizations and statistical techniques will be employed to uncover trends, seasonality patterns, and potential relationships within the data. 
Model Building and Evaluation:
# SARIMA:
A SARIMA model will be fitted to capture seasonal patterns and potential stationarity issues in the data. The model's hyperparameters (order and seasonal order) will be optimized through techniques like grid search to achieve the best possible fit.
# ARIMA: 
An ARIMA model will also be built for comparison purposes, potentially offering insights into non-seasonal aspects of the price movements.
Both models will be evaluated on unseen data using metrics like Mean Squared Error (MSE) or Mean Absolute Error (MAE) to assess their forecasting accuracy.
# Visualization and Interpretation:
Analyze the performance of the fitted models through diagnostic plots.
Compare observed vs. forecasted closing prices to evaluate the effectiveness of the predictions.
Potentially visualize year-wise summaries of closing prices or other relevant statistics.
# Comparison and Discussion:
The project will compare the performance of SARIMA and ARIMA models, drawing conclusions about their suitability for forecasting TorrentPower stock prices. The limitations of these statistical models and potential areas for future exploration will also be discussed.
