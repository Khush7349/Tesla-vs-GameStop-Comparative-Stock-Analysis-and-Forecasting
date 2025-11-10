# 🚀 Tesla vs GameStop — Comparative Stock Analysis & Forecasting

This project presents a complete data science analysis of **Tesla (TSLA)** and **GameStop (GME)** stocks, comparing their price movements, volatility, correlations, and future forecasts using ARIMA time series models.  
The goal is to understand how these two very different companies behaved in the stock market and predict short-term trends based on historical data.

---

## 📘 Project Overview

The analysis covers the full workflow of a data science project:
1. **Data Loading and Cleaning** — reading stock price data for Tesla and GameStop.  
2. **Exploratory Data Analysis (EDA)** — studying trends, price movements, and volatility.  
3. **Feature Engineering** — calculating returns, rolling averages, and volatility metrics.  
4. **Data Visualization** — plotting historical comparisons and performance metrics.  
5. **ARIMA Forecasting** — building statistical models to predict future prices for both stocks.  
6. **Insights and Conclusions** — interpreting patterns and forecasting results.

The project was developed in a **Kaggle environment** using Python and popular data science libraries.

---

## 📂 Datasets

This analysis uses two publicly available Kaggle datasets:

| Company | Dataset | Link |
|----------|----------|------|
| **Tesla (TSLA)** | Tesla Stock Data (Updated till June 2021) | [View Dataset](https://www.kaggle.com/datasets/rpaguirre/tesla-stock-data-updated-till-28jun2021) |
| **GameStop (GME)** | GameStop Historical Stock Prices | [View Dataset](https://www.kaggle.com/datasets/michaelbryantds/gamestop-historical-stock-prices) |

Both datasets contain daily stock prices with columns for date, open, high, low, close, adjusted close, and trading volume.

---

## 🧠 Key Analyses & Features

### 1️⃣ Exploratory Analysis
- Historical stock price trends for both companies.  
- Comparison of adjusted close prices over time.  
- Calculation of daily returns and volatility.  
- Visualization of rolling 30-day volatility and 50-day moving averages.

### 2️⃣ Comparative Insights
- **Tesla** shows strong long-term growth, driven by business fundamentals.  
- **GameStop** experienced a short-lived, speculative price spike in early 2021.  
- The two stocks show **low correlation (~0.1)**, meaning their price movements are largely independent.

### 3️⃣ Forecasting with ARIMA
- Applied **ARIMA(5,1,0)** model to predict the next 12 months of prices.  
- Tesla shows a steady upward trend with a broad confidence range.  
- GameStop shows high uncertainty and volatility in its forecast.  
- Forecast results saved as CSV for reproducibility.

---

## 📊 Visualizations

The notebook includes multiple professional-grade visualizations:
- Adjusted close price comparison (TSLA vs GME)  
- Normalized price growth (indexed at 1.0)  
- Daily return distributions and density plots  
- Rolling volatility and moving average charts  
- Correlation heatmap of daily returns  
- 12-month ARIMA forecasts with confidence intervals  

These visualizations were created using **Matplotlib** and **Seaborn**, ensuring readability and clarity.

---

## ⚙️ Tools & Libraries Used

- **Python 3.11**  
- **Pandas** — data manipulation and cleaning  
- **NumPy** — numerical computation  
- **Matplotlib / Seaborn** — visualization  
- **Statsmodels (ARIMA)** — time series modeling  
- **Warnings / Datetime / OS** — system utilities  

All libraries are included in the default Kaggle Python environment — no additional installations are required.

---

## 🔮 Results & Observations

- Tesla exhibits a **consistent upward trajectory** with controlled volatility.  
- GameStop displays **short-term extreme fluctuations**, largely event-driven.  
- Both stocks have distinct investor behaviors and risk profiles.  
- ARIMA forecasts suggest mild growth for Tesla and continued unpredictability for GameStop.  

These results align with real-world financial patterns: Tesla’s growth is sustainable, while GameStop’s surge reflects retail speculation.

---

## 🚀 Future Improvements

This project can be extended and enhanced in several directions:

- 🧠 **Sentiment Analysis** — Incorporate data from Twitter, Reddit, or financial news to analyze investor sentiment and its impact on stock prices.  
- 📉 **Advanced Forecasting Models** — Experiment with **LSTM**, **Prophet**, or **XGBoost** models for better non-linear forecasting performance.  
- 📊 **Interactive Dashboards** — Build live dashboards using **Plotly Dash** or **Streamlit** for real-time stock visualization and analysis.  
- 🌎 **Sector Comparison** — Expand the analysis to include other EV (Electric Vehicle) and retail industry competitors for broader insights.  
- 📅 **Automated Data Pipeline** — Schedule daily data updates using APIs like **yfinance** to keep forecasts and plots current.  
- 🧩 **Feature Expansion** — Include macroeconomic indicators like interest rates, inflation, and oil prices to study external correlations.  

---

## 👩‍💻 Author

**[KHUSHI SHARMA]**  
Data Science Enthusiast | Data Analytics Enthusiast   

---

> *Developed as a Kaggle-based data science project exploring real-world financial trends through Python, statistics, and visualization.*

