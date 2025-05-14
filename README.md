🧠 Project Title: Macro Impact FX Prediction EUR/USD with ML and SHAP

🚀 Project Overview
This project explores the quantitative relationship between macroeconomic indicators and the EUR/USD exchange rate using explainable machine learning. It integrates data wrangling, technical and macroeconomic analysis, regime modeling, model interpretability, and scenario simulation into a complete FX forecasting framework. SHAP values are used to provide transparency into the model’s decision-making process.

✅ What This Project Demonstrates
End-to-end FX and macro modeling workflow
Quantitative macro impact analysis on FX trends
Hands-on use of technical indicators and time-series features
Machine learning (Random Forest, Decision Tree) for classification
Regime detection using Gaussian HMMs
Model interpretability using SHAP
Feature drift detection using KS-test and JS divergence
Macro scenario shock simulation with SHAP delta analysis
Fully built in Python using free and open data

🧱 Key Modules & Steps

📥 Data Collection
EUR/USD FX rate via yfinance
Macroeconomic indicators from FRED:
US 10-Year Treasury Yield (DGS10)
Federal Funds Rate (FEDFUNDS)
US CPI Inflation (CPIAUCSL)
US Dollar Index (DTWEXBGS)

🧹 Data Wrangling
Date alignment and frequency normalization
Handling missing values
Calculating returns and percentage changes
Creating lag features for predictive modeling

📊 Exploratory Analysis
Visualizations of EUR/USD alongside macro trends
Rolling correlation plots (EUR/USD vs CPI, DXY, etc.)
Rolling volatility using standard deviation

📈 Strategy Backtesting
Simple Moving Average (SMA) crossover (50 vs 200)
Backtest comparison vs Buy & Hold
Sharpe ratio, drawdowns, and equity curve

🤖 Machine Learning Models
Random Forest and Decision Tree Classifiers
Features: RSI, MACD, SMA_diff, lagged returns, macro changes
Evaluation via accuracy, precision, recall, confusion matrix

🧠 Macro Regime Detection
Gaussian Hidden Markov Model (HMM) to infer economic states
Regime labels integrated into FX modeling
Regime overlay visualization on FX trend

🧪 Drift Monitoring
Rolling SHAP value trends to detect feature impact drift
Statistical tests (KS-test, JS divergence) to detect distributional shifts in macro features and regimes

🔬 Scenario Simulation & SHAP Analysis
Simulate macro shocks (e.g., CPI spike, Fed hike)
Recompute SHAP values and plot differential feature contributions
Measure and visualize model sensitivity to macro changes

📊 Visualizations Used
Time series of EUR/USD
Overlaid macroeconomic indicators and FX
Correlation and volatility heatmaps
SHAP feature attribution plots
SHAP delta bar charts for scenario comparison
Regime sequence plots

📦 Python Libraries Used
pandas, numpy, yfinance, matplotlib, seaborn, scikit-learn, ta, shap, fredapi, xgboost, hmmlearn, scipy

📃 License
This project is released under the MIT License and built entirely using open data and open-source tools.

