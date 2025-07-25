# zidio-development
# Overview
This project implements and compares four different time series forecasting models to predict stock prices: ARIMA (AutoRegressive Integrated Moving Average), SARIMA (Seasonal ARIMA), Prophet (Facebook's time series forecasting tool), and LSTM (Long Short-Term Memory neural network). The analysis focuses on Apple stock data spanning from 2018 to 2023, providing a robust comparison of traditional statistical methods against modern machine learning approaches for financial time series prediction.

# Features
The project offers a multi-model comparison framework with comprehensive performance metrics including RMSE, MAE, and MAPE calculations. Interactive visualizations are created using Plotly to display forecasting results and model comparisons. Each model generates 30-day future predictions with detailed error analysis, culminating in a model accuracy dashboard that presents detailed metrics in an easy-to-understand format. The implementation includes both statistical diagnostics and visual validation of model performance.

#📈 Models Performance
The performance analysis reveals that ARIMA achieved the best overall accuracy with an RMSE of 6.18, MAE of 4.82, and MAPE of 3.21%. SARIMA followed closely with slightly higher error metrics (RMSE: 6.24, MAE: 4.85, MAPE: 3.24%), while Prophet showed consistent performance with RMSE of 6.31, MAE of 4.91, and MAPE of 3.28%. The LSTM model, despite its complexity, recorded the highest error rates with RMSE of 6.42, MAE of 5.02, and MAPE of 3.35%, suggesting that for this particular dataset and timeframe, traditional statistical methods outperformed the deep learning approach
