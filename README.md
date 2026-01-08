# air-passengers-time-series-forecasting1
# Air Passengers Time Series Forecasting

## Problem Statement
The goal of this project is to forecast monthly airline passenger traffic using historical time series data.

## Dataset
- Monthly airline passenger data from 1949 to 1960
- Features:
  - Month
  - Number of Passengers

## Approach
- Time series visualization
- Stationarity check using ADF test
- Log transformation and differencing
- SARIMA (Seasonal ARIMA) model

## Model
SARIMA(1,1,1)(1,1,1,12)

## Results
- The model successfully captures trend and seasonality
- Forecasted passenger demand for the next 24 months
- Mean Absolute Error (MAE) ≈ 96

## Technologies Used
- Python
- Pandas, NumPy
- Statsmodels
- Matplotlib

## Future Improvements
- Add confidence intervals
- Deploy using Streamlit
- Compare with LSTM model

