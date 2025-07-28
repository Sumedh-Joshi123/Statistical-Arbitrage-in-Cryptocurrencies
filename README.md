# 📊 Statistical Arbitrage in Cryptocurrencies

This project explores statistical arbitrage strategies in cryptocurrency markets, applying both **momentum** and **reversal** logic to historical price and volume data.

---

## 🚀 Objective
The goal is to uncover price-volume patterns that predict returns using:
- **Momentum strategies** (on longer time horizons)
- **Reversal strategies** (on shorter time horizons)

I tested these strategies across a diverse crypto universe using raw price data, rank-based logic and volatility-adjusted weighting.

---

## 🧠 Strategy Highlights

### Momentum
- Based on rolling return rankings over multiple horizons
- Cross-sectional z-score normalization
- Top-ranked coins are longed and rebalanced regularly

### Reversal
- Short time-frame lookback
- Reversal entries based on extreme returns and quantile triggers
- Higher reversal strength during low-activity or liquidation periods

---

## 📈 Key Evaluation Metrics
- Cumulative PnL
- Sharpe Ratio
- Volatility
- Max Drawdown
- Market vs Limit Order execution (20 bps vs 7 bps)

Visual overlays compare strategies by coin, order type, and lookback window.

---

## ⚙️ Running the Notebook
Open in Jupyter or VSCode. It will:
- Fetch crypto data from Binance (via API)
- Run backtests on multiple strategies
- Output PnL plots and strategy metrics

> ⚠️ Internet access required to fetch data


