# 📊 TradingView Multi-Strategy Buy/Sell Alert Script

This repository contains a custom Pine Script indicator for TradingView that generates **Buy and Sell alerts** using a combination of:

- ✅ RSI + MACD crossover strategy
- ✅ EMA crossover (Golden Cross / Death Cross)
- ✅ Support and Resistance breakout detection

Designed for crypto and forex traders who want clean visual signals and alert-ready automation.

---

## 🚀 Features

- 🔔 Buy/Sell alerts based on multiple conditions
- 📈 Plots EMA 50 and EMA 200 for trend analysis
- 🧠 Supports RSI & MACD-based entries
- 📊 Detects breakouts above resistance and below support
- ✅ Compatible with TradingView alerts (Web/Email/App)

---

## 📜 Strategy Logic

### ✅ **Buy Signal triggers when**:
- RSI < 30 **and** MACD line crosses **above** the signal line
- OR EMA 50 crosses **above** EMA 200 (Golden Cross)
- OR Price **breaks above** recent resistance level

### ❌ **Sell Signal triggers when**:
- RSI > 70 **and** MACD line crosses **below** the signal line
- OR EMA 50 crosses **below** EMA 200 (Death Cross)
- OR Price **breaks below** recent support level

---

## 🖥️ How to Use

1. Go to [TradingView](https://tradingview.com)
2. Open any chart (e.g., BTC/USDT)
3. Click on **Pine Editor** (bottom panel)
4. Paste the contents of `strategy.pine` (from this repo)
5. Click ✅ **"Add to Chart"**
6. Set up alerts using the `Buy Signal` or `Sell Signal` conditions

---

## 🔔 Setting Alerts in TradingView

1. Click the **alarm clock icon** in the top menu
2. Click “Create Alert”
3. Under **Condition**, choose this script
4. Select `Buy Signal` or `Sell Signal`
5. Set frequency to `Once Per Bar Close` (recommended)
6. Choose your desired alert method (popup, email, webhook, etc.)

---

## 📂 Files

| File | Description |
|------|-------------|
| `strategy.pine` | Pine Script strategy code for TradingView |
| `README.md` | This documentation file |

## 🧠 Author

**Madhuranga Lakshan** 

## 📝 License

MIT License — feel free to use, modify, and share!
