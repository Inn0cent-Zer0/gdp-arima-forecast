# 📊 GDP Time Series Forecasting using ARIMA in R

## 📝 Description

This project demonstrates time series forecasting of quarterly GDP data using ARIMA models in R. It covers data loading, visualization, stationarity testing, model selection via AIC, residual diagnostics, and forecasting future GDP values. The project showcases practical application of statistical time series methods using popular R libraries.

## 📂 Dataset

* Dataset: `GDP.xlsx` (Quarterly GDP values)
* Time period: 1959 Q1 to 2001 Q1

## 🔑 Key Steps

* Data import and transformation to time series (`ts`) object
* Visualization of time series, ACF and PACF plots
* Stationarity check using Augmented Dickey-Fuller (ADF) test
* ARIMA model fitting with `auto.arima()` function using AIC
* Residual analysis with ACF, PACF and Ljung-Box test
* Forecasting next 10 years (40 quarters) of GDP with 95% confidence intervals
* Visualization of forecast results

## 🛠️ Libraries Used

* `readxl` for Excel data import
* `forecast` for ARIMA modeling and forecasting
* `tseries` for stationarity test

## 📈 Results

* Selected ARIMA model and its parameters
* Forecasted GDP values with 95% confidence intervals
* Residual diagnostics supporting model adequacy

## ▶️ How to Run

1. Ensure you have R and required packages installed (`readxl`, `forecast`, `tseries`).
2. Place `GDP.xlsx` in your working directory or update the path in the script.
3. Run the R script `ARIMA.R` to execute the full analysis and forecasting.
