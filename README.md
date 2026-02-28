# Nifty_200_quantitative-_trading_stratergy
# 📈 NIFTY 200 Quantitative Trading Strategy (Python)

## 🚀 Project Overview

This project implements a complete quantitative trading workflow on the **NIFTY 200 Index** using Python.

The entire workflow — from data download to backtesting and performance evaluation — is implemented inside a single Jupyter Notebook:

📓 `nifty200_quant_strategy_backtest.ipynb`

---

## 🎯 Objective

To design, test, and evaluate a rule-based systematic trading strategy using historical market data.

The goal is to compare:

- 📊 Market Returns  
- 📈 Strategy Returns  
- ⚖ Risk-adjusted Performance  

---

## 📊 Strategy Logic

### Indicator Used:
20-Day Simple Moving Average (SMA)

### 📌 Buy Condition
Close Price > 20-Day Moving Average

### 📌 Sell Condition
Close Price < 20-Day Moving Average

The strategy enters long positions when price trades above its moving average and exits when it falls below.

---

## 🧠 Performance Metrics Calculated

- Total Return
- Cumulative Strategy Return
- Market vs Strategy Comparison
- Annualized Volatility
- Sharpe Ratio

---

## 🗂 Project Structure

```
nifty200-quant-strategy/
│
├── nifty200_quant_strategy_backtest.ipynb
├── requirements.txt
├── README.md
└── .gitignore
```

---

## ⚙️ Tech Stack

- Python
- Pandas
- NumPy
- yfinance
- Matplotlib
- OpenPyXL

---

## 📅 Data Source

Historical daily data downloaded using:

`yfinance` library  

Symbol: `^CNX200`  
Custom date range supported  

---

## ▶ How To Run

### 1️⃣ Clone Repository

```
git clone https://github.com/yourusername/nifty200-quant-strategy.git
cd nifty200-quant-strategy
```

### 2️⃣ Install Dependencies

```
pip install -r requirements.txt
```

### 3️⃣ Run Notebook

```
jupyter notebook
```

Open:

`nifty200_quant_strategy_backtest.ipynb`

---

## 📈 Output

The notebook generates:

- Clean historical dataset
- Strategy signal column
- Backtested returns
- Cumulative return comparison
- Risk-adjusted performance metrics

---

## 💼 Applications

This framework can be extended for:

- Multi-stock portfolio strategies
- Intraday trading systems
- Risk management modeling
- Strategy optimization
- Algorithmic trading research

---
## ⚠ Disclaimer

This project is for educational and research purposes only. It does not constitute financial advice.

---

## 👤 Author

Pradip Jagdale
