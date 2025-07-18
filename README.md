# Energy‑Forecasting‑Project

This repository hosts a Jupyter Notebook that automates electricity‑consumption forecasting for a microgrid using an ensemble of time‑series models via AutoTS.

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

## Key Features

- **End‑to‑end pipeline** from data loading to final forecasts  
- **Ensemble blending** for improved accuracy and robustness  
- **Rich visualisations** for both data insights and model evaluation  
- **Modular design** allowing easy swap‑in of other time‑series datasets  

---
