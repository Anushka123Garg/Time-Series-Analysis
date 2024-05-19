# Comparative Analysis of Time Series Models for Weather Prediction

# Importing Dependencies

# Data Description [Target_Variables]
1. ManuaLoaDailyTemps  [AvgTemp]
2. JaipurFinalCleanDataset  [meantempm]
3. DailyDelhiClimate   [meantemp]
4. WeatherData   [Temp_C]

# Model Selection
1. ARIMA (AutoRegressive Integrated Moving Average)
   1. Moving Average Model
   2. Auto Regressive Model

3. Recurrent Neural Networks
   
5. Long Short-Term Memory

# Evaluation Metric
   Root mean squared error (RMSE)

# Results & Observations

![bar_graph](https://github.com/Anushka123Garg/Time-Series-Analysis/assets/98416741/7513659b-0d17-4f47-b67d-e1492605ebcd)
Bar Graph showing RMSE on the y-axis and datasets with different models on the X-axis.

![AvgTemp](https://github.com/Anushka123Garg/Time-Series-Analysis/assets/98416741/14c44795-0513-4c85-b131-47e8fe29e488)
Bar Graph showing RMSE on the y-axis and datasets with multivariate RNN & LSTM on the
X-axis where RNN1 is for target variable1 and RNN2 for target variable2 and same for LSTM1
and LSTM2.
