# Voughtazon Inc. - Time Series Forecasting

## Overview

This project implements a time series forecasting model to predict daily action figure sales for Voughtazon Inc. using historical sales data from 2010 to 2019.

### Key Steps:

- **Data Preprocessing**: Conversion to datetime, resampling, handling missing values, and exploratory data analysis.
- **Stationarity Testing**: ADF tests and differencing to ensure suitability for time series modeling.
- **Forecasting Models**:
  - **ARIMA**: Captures autoregressive patterns.
  - **Holt-Winters**: Captures trends using exponential smoothing.
- **Visualization**: Plots of daily sales trends, product/stall sales distribution, and actual vs. predicted forecasts.
- **Model Evaluation**: Metrics used include MAE, RMSE, MAPE, MPE, Min-Max Error, and Correlation.

## Key Insights

- Top-selling product types and stalls identified through descriptive analysis.
- Both ARIMA and Holt-Winters models show predictive power, with ARIMA slightly outperforming in most metrics.
- Stationarity achieved through first differencing, verified via statistical tests.

## Note

This activity is for educational purposes. **Dataset not included** `productsales.csv` is not included due to constraints.
