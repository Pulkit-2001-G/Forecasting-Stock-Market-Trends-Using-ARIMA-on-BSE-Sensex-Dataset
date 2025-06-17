# Forecasting-Stock-Market-Trends-Using-ARIMA-on-BSE-Sensex-Dataset

📈 Time Series Forecasting on BSE Sensex Using ARIMA Models
This project presents a comprehensive analysis of the BSE Sensex index using advanced time series modeling techniques, including ARIMA and SARIMAX. Building on a prior study that focused on foundational steps like data cleaning, stationarity testing (ADF), and differencing, this extended analysis incorporates:

1. Enhanced model specification with ARIMA(2,0,2)
2. Detailed model diagnostics (AIC/BIC, residual analysis, heteroskedasticity, normality tests)
3. Interpretation of coefficients and statistical significance
4. Real-world return forecasts expressed in percentage change terms
5. Discussion of challenges such as non-normal residuals and volatility clustering

⚠️ Although short-term forecast accuracy remains constrained due to high market volatility, this analysis demonstrates iterative learning in model selection, evaluation, and interpretation of financial time series data.

🔧 Key Techniques Used: 
1. Data preprocessing and return calculation
2. ADF test for stationarity
3. ARIMA and SARIMAX modeling via statsmodels
4. Residual diagnostics (Ljung-Box, Jarque-Bera, Heteroskedasticity test)
5. Forecast interpretation (log/simple returns)
6. Cumulative return to price transformation

📌 Lessons & Insights:

1.Financial time series often violate key ARIMA assumptions (e.g., homoskedasticity, normality)

2.Importance of robust diagnostics before interpreting forecasts

3.Value of continuous model refinement and iteration
