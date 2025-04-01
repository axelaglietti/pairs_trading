# 📊 Rolling Pairs Trading Strategy – Quant Finance Project

This project implements a **multi-pair statistical arbitrage strategy** using historical stock price data and rolling cointegration analysis. It simulates trading on the top 3 cointegrated equity pairs selected every 6 months over a 5-year period.

---

## 🚀 Project Summary

- **Assets Universe**: 8 major US equities (KO, PEP, XOM, CVX, MSFT, AAPL, JPM, BAC)
- **Strategy**: Pairs trading via spread mean reversion
- **Pair Selection**: Top 3 cointegrated pairs (by p-value) per 1-year rolling window
- **Signal**: Z-score of price spread (entry: ±1, exit: 0)
- **Capital**: $10,000, equally allocated across active pairs
- **Costs**: 0.1% per leg, deducted on every position change

---

## 📈 Key Features

- ✅ Rolling cointegration testing (dynamic regime awareness)
- ✅ Independent backtests per pair & aggregation of results
- ✅ Transaction cost simulation
- ✅ Portfolio performance curve
- ✅ Pair rotation chart (which pairs are selected when)
- ✅ Rolling Sharpe Ratio visualization
- ✅ Cleanly formatted for PDF reporting or Streamlit dashboards

---

## 📊 Results Snapshot

| Metric              | Value           |
|---------------------|------------------|
| Total Return        | ~621.19%          |
| Annualized Sharpe   | ~1.96            |
| Strategy Horizon    | Jan 2019 – Jan 2024 |


---

## 📂 Files

- `pairs_trading.ipynb`: Main notebook with full analysis and visualizations
- `README.md`: Project documentation

---

## 💡 Insights

- This strategy adapts over time to changing correlations
- Cointegration selection helps mitigate overfitting
- Rolling analysis mimics real-world rebalancing needs
- Strong Sharpe and smooth equity curve demonstrate practical robustness

---

## 🔧 Possible Extensions

- Compare against benchmark (e.g., SPY)
- Introduce leverage or stop-loss mechanics
- Apply to crypto or multi-asset ETFs
- Deploy a live dashboard with Streamlit

---

## 📬 Author

**Axel Aglietti Zampalla**  
M.S. in Management Science & Engineering @ Columbia University  
Python • Pandas • StatsModels • Financial Modeling  
[LinkedIn](https://www.linkedin.com/in/axel-aglietti)

---

