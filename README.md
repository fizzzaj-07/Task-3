# Task-3
Energy_Forecasting/README.md
# Task 3: Energy Consumption Time Series Forecasting

## Objective
Forecast short-term household energy usage using historical time-based patterns.

## Dataset
Household Power Consumption Dataset (Kaggle)

Key Feature:
- Global Active Power

## Methodology
1. Loaded and cleaned the dataset.
2. Parsed datetime and set it as index.
3. Resampled data to hourly frequency.
4. Engineered time-based features:
   - Hour of day
   - Day of week
   - Weekend indicator
5. Split data into training and testing sets.
6. Trained and compared multiple forecasting models.

## Models Used
- ARIMA
- Prophet
- XGBoost

## Evaluation Metrics
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Results
All three models were evaluated and compared.  
XGBoost performed best for short-term forecasting using time-based features.

## Visualization
- Actual vs forecasted energy consumption plots were generated for all models.

## Conclusion
Time-series forecasting combined with machine learning models provides accurate predictions for household energy usage.
