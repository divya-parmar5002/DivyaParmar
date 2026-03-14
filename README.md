# DivyaParmar
![MasterHead](https://user-images.githubusercontent.com/90236635/232446433-d5540fa2-fe28-4bb8-b929-cdb51fe61336.gif)
<h1 align="center">Hi 👋,I'm Divya Parmar</h1>
<h3 align="center">A passionate Data Scientist from India</h3>
<img align="right" alt="Coding" width="400" src="https://user-images.githubusercontent.com/74038190/236119160-976a0405-caa7-470c-9356-16d43402ea0a.gif"
- 🔭 I’m currently working on **video conferencing app**

- 🌱 I’m currently learning **Basic to Advanced concept of Machine learning and Data science **

- 📫 How to reach me **divyaparmar8046@gmail.com**

  📊 Time Series analysis with Cryptocurrency
🔹 Project Overview

Project Title: Time Series Analysis with Cryptocurrency

Problem Statement:
Cryptocurrency prices, especially Bitcoin, are highly volatile and time-dependent. The goal of this project is to:

Analyze historical Bitcoin price behavior

Understand trends, volatility, and risk

Forecast future prices using time series models

Present insights using interactive dashboards

Elevator Pitch:

“This project focuses on analyzing and forecasting Bitcoin prices using time series techniques and visual dashboards.”

🔹 Step 1: Data Collection & Understanding

Dataset Source: Yahoo Finance
Ticker: BTC-USD
Frequency: Daily
Time Period: 17 Sept 2014 – Jan 2026

Columns (OHLCV):

Column	Meaning
Open	Price at start of day
High	Highest price
Low	Lowest price
Close	Price at end of day
Volume	Trading volume

“I used daily OHLCV data which is standard for financial time series analysis.”

🔹 Step 2: Data Preprocessing

Key Steps:

Removed extra rows (Ticker & empty Date rows)

Renamed columns

Converted Date → datetime, Prices → numeric

Set Date as index and sorted by date

Checked & removed missing values

“Time series models require clean, ordered, and continuous data.”

🔹 Step 3: Exploratory Data Analysis (EDA)
Dashboard 1: Overview / Executive Summary

Bitcoin Price Trend: Line chart of Close price

“This chart highlights the long-term price evolution of Bitcoin.”

Volume Trend: Market participation indicator

“Volume indicates the strength and reliability of price movements.”

Dashboard 2: Price Explorer & Candlesticks

Candlestick Chart: Shows daily volatility & market sentiment

“Candlestick charts help analyze daily volatility and market sentiment.”

Moving Averages (MA30 & MA90): Smooth price fluctuations

“Moving averages reduce short-term noise and highlight long-term trends.”

Dashboard 3: Volatility & Risk Analysis

Daily Returns: Shows ups and downs clearly

Rolling Volatility (30-day): Measures market risk

“High rolling volatility confirms the risky nature of cryptocurrency markets.”

🔹 Step 4: Stationarity Check

ADF Test Result: p-value = 0.84 (>0.05) → Non-stationary

“ADF test confirmed that the Bitcoin price series is non-stationary, so differencing was required.”

🔹 Step 5: Train–Test Split

Train: Data till 2024

Test: Data from 2025 onwards

“Recent data was kept for testing to evaluate real-world forecasting performance.”

🔹 Step 6: ARIMA Model

Why ARIMA?

Handles trend

Suitable for non-stationary time series

Widely used in financial forecasting

Implementation:

ARIMA(1,1,1)

Forecasted test period

Compared Actual vs Forecast

“ARIMA was used as the baseline model for short-term Bitcoin price forecasting.”

🔹 Step 7: Model Evaluation

Metrics Used:

MAE (Mean Absolute Error)

RMSE (Root Mean Squared Error)

“Lower MAE and RMSE indicate better model accuracy.”

🔹 Step 8: Future Forecast (2026)

Forecasted next 365 days

Visualized future trend

“This provides a possible future price trajectory based on historical patterns.”

🔹 Step 9: SARIMA (Seasonal Analysis)

Why SARIMA?

To check if Bitcoin has seasonal behavior

Observation: Daily Bitcoin prices show weak/inconsistent seasonality

“SARIMA was evaluated to capture seasonality, but Bitcoin daily prices showed weak seasonal patterns.”

🔹 Step 10: Prophet Model

Why Prophet?

Handles trend & seasonality automatically

Easy to interpret & explain

Used in industry

“Prophet was used for interpretable long-term forecasting suitable for business insights.”

🔹 Step 11: Power BI Dashboard

Visualizations:

Price Trend

Candlestick Chart

Volatility

Forecast vs Actual

“Power BI was used to create interactive dashboards for better decision-making.”

🔹 Conclusion

“This project analyzed historical Bitcoin price data to understand trends, volatility, and risk. Time series models like ARIMA were used for short-term forecasting, SARIMA was evaluated for seasonality, and Prophet provided long-term interpretable forecasts. Visual dashboards were created to communicate insights effectively.”


