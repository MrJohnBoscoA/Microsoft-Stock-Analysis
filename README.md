# Microsoft Stock Price Analysis with Time Series Forecasting

## 📊 Project Overview
This project applies advanced time series forecasting techniques to predict Microsoft stock prices. Using ARIMA and SARIMA models, I compare classical statistical forecasting methods to identify the best approach for short-term stock price predictions.

## 🎯 Objective
- Analyze historical Microsoft stock price data (trend & seasonality)
- Build and compare ARIMA and SARIMA forecasting models
- Evaluate model performance on validation dataset
- Provide insights into model selection for financial forecasting

## 📁 Dataset
- **Source**: Microsoft (MSFT) historical stock data
- **Time Period**: Multiple years of daily closing prices
- **Features**: Date, Open, High, Low, Close, Volume
- **Target**: Daily closing price forecasts

## 🛠️ Technologies & Libraries
- **Python 3.x**
- **statsmodels**: ARIMA, SARIMA model implementation
- **pandas**: Time series data manipulation
- **NumPy**: Numerical computations
- **Matplotlib & Seaborn**: Visualization
- **scikit-learn**: Model evaluation metrics

## 🔍 Methodology
1. **Data Loading & Preparation**: Handle missing values, convert to time series
2. **Exploratory Analysis**: Visualize trends, seasonality, ACF/PACF plots
3. **Stationarity Testing**: ADF test, differencing if needed
4. **ARIMA Modeling**: Parameter tuning, model fitting, diagnostics
5. **SARIMA Modeling**: Capture seasonality patterns
6. **Model Comparison**: Compare RMSE, MAE, and forecast accuracy
7. **Forecasting**: Generate predictions and visualize results

## 📈 Key Findings
- Detailed comparison of ARIMA vs SARIMA performance
- Model diagnostics and residual analysis
- Forecast accuracy metrics and interpretations

## 🚀 How to Run
```bash
jupyter notebook Microsoft Stock Analysis.ipynb
```

## 📁 Files
- `Microsoft Stock Analysis.ipynb`: Complete time series analysis
- `Microsoft_Stock.csv`: Historical stock data
- `README.md`: This file

## 📚 Model Details
- **ARIMA(p,d,q)**: Autoregressive Integrated Moving Average
- **SARIMA(p,d,q,P,D,Q,m)**: Seasonal ARIMA for capturing seasonality
- See notebook for parameter selection and justification

## 🚀 Applications
- Financial forecasting and investment planning
- Risk assessment for portfolio management
- Learning resource for time series analysis

## 👨‍💻 Author
John Bosco A | Data Analyst | Data Science Student

## 📌 Tags
time-series-forecasting • machine-learning • python • data-analysis
