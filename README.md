# ⚡ Indian Power Sector Financial Analysis System

This project presents a comprehensive financial analysis system for selected companies in the Indian power sector using historical stock market data. The primary objective is to evaluate risk, return, and trading opportunities through a data-driven approach. 📈

## 🚀 Project Overview
The study integrates multiple analytical components to provide a 360-degree view of investment viability, combining market risk assessment, credit risk modeling, portfolio analysis, and rule-based trading strategies.

## 🛠️ Technical Workflow

### 📊 Data Acquisition & Preprocessing
* **Data Source:** Historical stock price data (2020–2024) collected via the `yfinance` library. 📥
* **Processing:** Data was preprocessed to calculate daily returns and ensure consistency for downstream analysis.
* **Exploratory Analysis:** Used price trends, normalized comparisons, and correlation heatmaps to decode stock behavior. 🔍

### 🛡️ Risk Analysis
* **Market Risk:** Evaluated through volatility, maximum drawdown, and rolling volatility to quantify price fluctuations and downside risk. 📉
* **Credit Risk:** Developed a scoring model using key financial ratios, including **Debt-to-Equity** and **Return on Equity (ROE)**, to categorize companies by risk level. 💳
* **Value at Risk (VaR):** Quantified potential losses at a 95% confidence level to establish safety margins. ⚠️

### 💼 Portfolio & Strategy
* **Portfolio Construction:** Created an equal-weighted portfolio to analyze diversification benefits. ⚖️
* **Performance Metrics:** Calculated total return, volatility, and the **Sharpe Ratio** to measure risk-adjusted returns.
* **Trading Strategy:** Implemented a **Moving Average Crossover** strategy to generate buy/sell signals, benchmarked against a traditional buy-and-hold approach. 💹

## 🎯 Key Results
The comparative analysis between individual stocks and the diversified portfolio highlights the critical trade-off between risk and return. The results demonstrate that combining multiple analytical techniques significantly improves the quality of informed investment decision-making. ✅
