 Task 3: Energy Consumption Time Series Forecasting
Objective

Forecast short-term household energy usage using historical power consumption patterns.

Dataset

**Household Power Consumption Dataset**
Features include Date, Time, Global Active Power, Voltage, and sub-metering readings.

 Approach

1. **Data Preparation**

   * Combined Date and Time into a single datetime index.
   * Converted power consumption values to numeric.
   * Resampled data into hourly averages.
2. **Feature Engineering**

   * Extracted time-based features (hour, weekday/weekend).
3. **Modeling**

   * Compared three models:

     * **ARIMA** (classical time series)
     * **Prophet** (trend & seasonality)
     * **XGBoost Regressor** (machine learning)
4. **Evaluation**

   * Assessed models with **MAE** and **RMSE** metrics.
   * Visualized actual vs. forecasted consumption.

 Results & Insights

* Prophet provided smooth and interpretable trend detection.
* XGBoost gave the lowest RMSE, capturing nonlinear fluctuations.
* Energy usage peaks observed during evening hours and weekdays.

 Skills Gained

* Time series analysis and forecasting
* Feature engineering for temporal data
* Model evaluation and comparison (MAE, RMSE)
* Visual trend interpretation and forecasting insights
