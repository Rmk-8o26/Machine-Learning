# Power Consumption Forecasting (LSTM)

Forecast **household electric power consumption** using an LSTM deep learning model.

## Pipeline
- Data loading from UCI dataset (~2M rows)
- Stationarity testing (ADF test)
- Partial autocorrelation (PACF) analysis for lag selection
- Sequence creation with lookback window
- MinMax scaling
- LSTM model architecture: LSTM layers + Dropout + Dense
- Early stopping callback
- Inverse transform and evaluation (RMSE, MAE)

## Dataset
- `data.zip` — UCI Individual Household Electric Power Consumption
- ~2M rows, 9 columns (date, time, global active power, voltage, sub-metering, etc.)

## Requirements
```
pip install -r requirements.txt
```
