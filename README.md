# Predictive Modeling of Gold Prices Using Econometrics & Machine Learning

## 📊 Project Overview
Developed a dual-stage forecasting model to identify the primary drivers of Gold price returns over a 15-year period (2008–2023). This project bridges traditional macroeconomic theory with modern machine learning techniques.

## 🔬 Methodology
* **Econometrics (Linear Thinking):** Constructed a Multivariate OLS Regression model to test the "Safe Haven" and "Inflation Hedge" hypotheses. Quantified the inverse correlation with the S&P 500 and the positive correlation with Crude Oil (USO).
* **Machine Learning (Non-Linear Dynamics):** Engineered a Random Forest Regressor in Python to capture non-linear market behavior. Implemented technical feature engineering, including Relative Strength Index (RSI) and Rolling Volatility (20-day standard deviation).

## 💡 Key Findings
Through Feature Importance analysis, the model revealed that **Market Volatility** and **Momentum (RSI)** are significantly stronger predictors of short-term price direction than external macro-factors (Oil/USD). This suggests that market psychology and panic outweigh traditional fundamentals in short-term trading windows.

## 🛠️ Tools & Stack
* **Languages:** Python, SQL (Concept), Excel
* **Libraries:** Pandas, Scikit-Learn, Seaborn, Matplotlib, yfinance
* **Techniques:** OLS Regression, Random Forest, Feature Engineering, Time Series Analysis

## 🚀 How to Run
1. Clone the repository.
2. Ensure you have `yfinance`, `pandas`, `scikit-learn`, and `seaborn` installed.
3. Run `gold_prediction_model.py` to fetch live market data, train the AI, and generate the feature importance charts.
