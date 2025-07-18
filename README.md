# Energy‑Forecasting‑Project

I spent some time working with time series forecasting models and found Auto ARIMA and AutoTS to be very effective. In this repository I compare and analyse these models to see how they automate electricity‑consumption forecasting for a microgrid.

---

## Notebook Overview

1. **Exploratory Data Analysis**  
   - Imports and inspects historical consumption data  
   - Visualises trends, seasonality and autocorrelations  
   - Runs stationarity tests (ADF, KPSS) and seasonal decomposition  

2. **Model Building**  
   - Fits an Auto ARIMA baseline model  
   - Trains an AutoTS ensemble (stacked blending) across multiple algorithms  
   - Generates forecasts for a defined future horizon  

3. **Performance Comparison**  
   - Compares ARIMA vs AutoTS ensemble outputs  
   - Reports error metrics (RMSE, MAE, MAPE)  
   - Plots actual vs forecasted consumption with confidence intervals  

---
