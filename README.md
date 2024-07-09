# BTC Price Prediction

# Overview
This project aims to predict the 7-day Return on Investment (ROI) of Bitcoin (BTC) using historical price data. The model uses Exponential Smoothing with trend and seasonality components to forecast the weekly ROI from Monday to Monday.

# Introduction
Bitcoin price prediction is an essential task for investors and traders. This project uses historical BTC price data to predict the 7-day ROI using an Exponential Smoothing model. The model is evaluated using Mean Absolute Error (MAE) and aims to provide accurate forecasts for weekly returns.

# Data Collection
We collect historical BTC price data from Yahoo Finance. The dataset includes daily prices from September 16, 2014, to the current date.

# Data Processing
The data is processed to calculate the 7-day ROI from Monday to Monday. This ROI is used as the target variable for the model.

# Modeling
An Exponential Smoothing model with trend and seasonality components is used for the prediction. The model is trained on historical ROI data and evaluated using rolling forecasts.

# Forecasting
The trained model is used to forecast the 7-day ROI for the week from July 8th to July 15th. The forecast is provided in percentage format.

# Results
The model's performance is evaluated using Mean Absolute Error (MAE). The forecasted ROIs for the evaluation period and the final forecast for the specified week are presented.

# License
This project is licensed under the MIT License. See the LICENSE file for more details.

