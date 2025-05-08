🧠 Project Title: Macro Impact FX Prediction EUR/USD with ML and SHAP

🚀 Project Overview:
This project explores the quantitative relationship between macroeconomic indicators and the EUR/USD exchange rate. We apply data wrangling, technical analysis, macro correlation, and machine learning models to forecast daily FX direction. SHAP values provide transparency into the model’s decision-making.

✅ What This Project Demonstrates:
End-to-end FX and macro modeling workflow
Quantitative macro impact analysis on FX trends
Hands-on use of technical indicators and time-series features
Machine learning (Random Forest, Decision Tree) for classification
Model interpretability using SHAP
Fully built in Python using only free and open data

🧱 Key Modules & Steps:
1. 📥 Data Collection
FX Rate: EUR/USD via yfinance
Macro Indicators from FRED:
US 10-Year Treasury Yield (DGS10)
Federal Funds Rate (FEDFUNDS)
US Inflation CPI (CPIAUCSL)
US Dollar Index (DTWEXBGS)
Fallback to EUR/USD only if FRED not working

2. 🧹 Data Wrangling:
Date alignment, missing value handling
Percentage changes for macro indicators
Return calculations and lag creation

3. 📊 Exploratory Analytics:
Line charts for FX + macro trends
Rolling correlation (EUR/USD vs CPI, DXY, etc.)
Rolling volatility using standard deviation
Visual overlays of macro vs FX behavior

4. 📈 Strategy Backtest:
Simple SMA crossover (50 vs 200)
Returns & strategy equity curve
Sharpe ratio and drawdown comparison with Buy & Hold

5. 🤖 Machine Learning Models:
Train Decision Tree & Random Forest to classify direction
Use lagged returns, RSI, MACD, SMA_diff, etc. as features
Evaluate with confusion matrix, accuracy, precision/recall

6. 🔍 Explainability with SHAP:
SHAP summary plots to interpret model behavior
Identify most influential features (e.g. RSI, MACD)
Explore which factors drove predictions up/down

📊 Visualizations Used:
EUR/USD time-series trend
Macro + FX overlays
Rolling correlation heatmap
Volatility charts
Model accuracy and SHAP feature bars

📦 Libraries Used:
pandas, numpy, yfinance, matplotlib, seaborn, scikit-learn, ta, shap, fredapi

📃 License
This project is released under the MIT License.
