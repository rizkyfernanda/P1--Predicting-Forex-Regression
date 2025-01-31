# Predicting EUR-IDR rates using Regression Models
A general consensus states that the EUR-IDR rates will increase over time. Using Linear Regression model and Seasonal ARIMA model, I have predicted what would be the rates for years to come (2026 to 2030).

Below are the current rates.

![Current EUR-IDR Exchange Rates](https://github.com/rizkyfernanda/P1--Simple-Forex-Regression/blob/main/graphs/1-currentrates.png)

Below are the predictions using Linear Regression model with R2 score of 0.44. This graph has predicted that EUR-IDR rates will reach Rp18,000 a few years later.

![Linear Regression Predictions](https://github.com/rizkyfernanda/P1--Simple-Forex-Regression/blob/main/graphs/2-linear.png)

Below are the predictions using Seasonal ARIMA model with R2 score of 0.64 (which means might be potentially more accurate compared to using Linear Regression). This graph has predicted that EUR-IDR rates will reach Rp20,000 faster compared to what the Linear Regression model had predicted.

![Seasonal ARIMA Predictions](https://github.com/rizkyfernanda/P1--Simple-Forex-Regression/blob/main/graphs/3-arima.png)

For the next step, we might apply a Neural Network / LSTM to the ARIMA model for iteratively improving the prediction trend.

# Dataset

Asaniczka. (2025). Forex Exchange Rates Since 2004 (Updated Daily) [Data set]. Kaggle.

Website: https://www.kaggle.com/datasets/asaniczka/forex-exchange-rate-since-2004-updated-daily

DOI: 10.34740/kaggle/dsv/10558683
