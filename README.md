# Data Science & Analytics Portfolio
<p align="left">
  <a href="https://www.python.org/"><img alt="Python 3.9+" src="https://img.shields.io/badge/python-3.9%2B-blue?logo=python"></a>
  <img alt="pandas" src="https://img.shields.io/badge/pandas-used-150458?logo=pandas&logoColor=white">
  <img alt="statsmodels" src="https://img.shields.io/badge/statsmodels-used-4B8BBE">
  <img alt="matplotlib" src="https://img.shields.io/badge/matplotlib-used-11557C">
  <img alt="seaborn" src="https://img.shields.io/badge/seaborn-used-4C72B0">
  <a href="./License"><img alt="License: MIT" src="https://img.shields.io/badge/License-MIT-green.svg"></a>
</p>


This repo highlights applied projects in **text analytics**, **forecasting**, and **regression**.  
All public datasets here are **synthetic or public**—no sensitive data.

---

## 📁 Projects

### 1) Milkshake Sales Forecasting — OLS (lags & weather) vs ARIMA/SARIMAX
- 🔗 **Project page:** [milkshake-forecasting/README.md](milkshake-forecasting/README.md)
- 📓 **Notebook:** [milkshake-forecasting/MilkshakeModeling.ipynb](milkshake-forecasting/MilkshakeModeling.ipynb)
- 🗂️ **Data:** [ItemSales_2023_2025.csv](milkshake-forecasting/ItemSales_2023_2025.csv), [Weather Data.csv](milkshake-forecasting/Weather%20Data.csv)
- ✨ **Outcome:** Best overall = **OLS (lags + weather)** — strongest point accuracy and interval calibration on the synthetic set.
<!-- Milkshake — headline figs -->
<p align="center">
  <a href="milkshake-forecasting/ols_lags_forecast.png">
    <img src="milkshake-forecasting/ols_lags_forecast.png" width="47%" alt="OLS (lags) forecast">
  </a>
  &nbsp;
  <a href="milkshake-forecasting/ols_lags_weather_forecast.png">
    <img src="milkshake-forecasting/ols_lags_weather_forecast.png" width="47%" alt="OLS (lags + weather) forecast">
  </a>
</p>

---

### 2) Competitive Analysis — Text Analytics
Compare sentiment and themes between two brands using NLP (sentiment, n-grams, light topic modeling).
- 🔗 **Project page:** [competitive-analysis/README.md](competitive-analysis/README.md)
- 📓 **Notebook:** [competitive-analysis/Competitive Analysis.ipynb](competitive-analysis/Competitive%20Analysis.ipynb)
- 🗂️ **Data:** [suck_it_up_reviews.csv](competitive-analysis/suck_it_up_reviews.csv), [brushy_mountain_reviews.csv](competitive-analysis/brushy_mountain_reviews.csv)

<!-- Competitive Analysis — headline figs -->
<p align="center">
  <a href="competitive-analysis/sentiment_compare.png">
    <img src="competitive-analysis/sentiment_compare.png" width="30%" alt="Sentiment by business">
  </a>
  &nbsp;
  <a href="competitive-analysis/top_unigrams_by_business.png">
    <img src="competitive-analysis/top_unigrams_by_business.png" width="30%" alt="Top unigrams by business">
  </a>
  &nbsp;
  <a href="competitive-analysis/top_bigrams_by_business.png">
    <img src="competitive-analysis/top_bigrams_by_business.png" width="30%" alt="Top bigrams by business">
  </a>
</p>

---

### 3) Storewide Sales Forecasting — Linear Models (Calendar vs Calendar+Weather)

- **Project page:** [store-sales-forecasting/README.md](store-sales-forecasting/README.md)  
- **Notebook:** [store-sales-forecasting/StoreSalesForecasting.ipynb](store-sales-forecasting/StoreSalesForecasting.ipynb)  
- **Data:** [StoreSales_Summary_23-24_synthetic.csv](store-sales-forecasting/StoreSales_Summary_23-24_synthetic.csv), [StoreSales_Summary_24-25_synthetic.csv](store-sales-forecasting/StoreSales_Summary_24-25_synthetic.csv), [Weather_Data_SYNTH.csv](store-sales-forecasting/Weather_Data_SYNTH.csv)

<!-- Storewide Sales — headline figs -->
<p align="center">
  <a href="store-sales-forecasting/ols_calendar_forecast.png">
    <img src="store-sales-forecasting/ols_calendar_forecast.png" width="47%" alt="OLS calendar-only forecast">
  </a>
  &nbsp;
  <a href="store-sales-forecasting/ols_calendar_weather_forecast.png">
    <img src="store-sales-forecasting/ols_calendar_weather_forecast.png" width="47%" alt="OLS calendar + weather forecast">
  </a>
</p>


**Headline (test set, dollars):**

| Model               | RMSE  | MAE   | % within $20 | PI coverage | Avg PI range |
|---------------------|------:|------:|-------------:|------------:|-------------:|
| Calendar only       | 89.98 | 59.49 | 50.70%       | 88.73%      | $790.84      |
| Calendar + weather  | 91.46 | 59.96 | 53.52%       | 91.55%      | $734.92      |



---

## 🛠️ Stack
Python (pandas, NumPy, scikit-learn, statsmodels, matplotlib, seaborn)

