# 🇮🇳 AI-Powered Indian Stock Market Dashboard (NSE/BSE)

A professional, end-to-end **AI + Technical Analysis Dashboard** for Indian stocks and indices.
Built using Streamlit, Plotly, yFinance, and Machine Learning — optimized for NSE/BSE data.

---

# 📌 Overview

This dashboard provides:

* Machine Learning–based **next-day price prediction**
* Advanced technical indicators and multi-panel charting
* AI-powered natural language **market insights**
* Performance analytics (Sharpe Ratio, Volatility, Drawdown)
* Clean, fast and interactive **Streamlit UI**
* Full support for India-specific tickers, indices, and ₹ formats

---

# 🚀 Features

## 🤖 Machine Learning

* Random Forest model for **next-day closing price prediction**
* Automated feature engineering (lags, rolling stats, volatility)
* Train/Test R² scores and confidence levels
* Top 10 most important features visualized

## 📈 Technical Analysis

* Candlestick charts with:

  * SMA 20/50/200
  * EMA 12/26
  * Bollinger Bands
* MACD, RSI, Stochastic Oscillator, ATR
* Volume trends + 20-day Volume SMA
* Multi-panel Plotly charts (dark theme)

## 🧠 AI Market Insights

* Auto-generated insights based on:

  * Price momentum
  * RSI zones
  * MACD crossovers
  * Bollinger Band position
  * Volume strength
  * Market cap category (Large/Mid/Small cap)

## 📊 Performance Analytics

* Total Return (%)
* Annualized Volatility
* Sharpe Ratio
* Max Drawdown
* Cumulative Returns chart

## 🇮🇳 Indian Market Support

* Works for NSE (.NS) and BSE (.BO)
* Supports indices:

  * **NIFTY 50 ( ^NSEI )**
  * **BANK NIFTY ( ^NSEBANK )**
  * **SENSEX ( ^BSESN )**
* Indian-style formatting (₹, Lakh, Crore)
* Auto-normalization for symbols (e.g., ENTER → ENTER.NS)

---

# 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **Plotly**
* **yFinance**
* **scikit-learn**
* **NumPy**, **Pandas**

---

# 📦 Installation

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

### 2. Run the App

```bash
streamlit run stock_dashboard.py
```

### 3. Open in Browser

```
http://localhost:8501
```

---

# 🎮 How to Use

1. Select **Exchange** — NSE or BSE
2. Pick a **stock or index** (or enter a custom symbol)
3. Choose **analysis period** (1 month → max history)
4. Toggle modules:

   * ML Price Prediction
   * Technical Charts
   * Performance Metrics
   * AI Market Insights
5. View results:

   * Interactive charts
   * Key metrics
   * Predictions
   * Market commentary

---

# 📊 Example Insights

* 🚀 *“Strong bullish momentum with a sharp price surge observed.”*
* ⚡ *“MACD bullish crossover — momentum improving.”*
* 💡 *“RSI near oversold zone — possible bounce setup.”*
* 🔥 *“High volume spike confirms strong conviction.”*

---

# 📁 Project Structure

```
├── stock_dashboard.py      # Main Streamlit application
├── requirements.txt        # Dependencies
└── README.md               # Documentation
```

---

# ⚠️ Disclaimer

This project is for **educational purposes only**.
Not financial or investment advice.
Market data is fetched from Yahoo Finance.

---

# ❤️ Made for India

Built with Python, Machine Learning, Streamlit, and love for the Indian markets.

---