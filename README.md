# Indian Financial Markets Historical Datasets (NSE, BSE & MCX)

Clean historical derivatives data for NSE, BSE, and MCX (1-min OHLCV & tick market depth data, 2015–2026) in CSV format. Built for quantitative researchers, backtesting algorithmic strategies, and option pricing models. 

---
---

## ✅ Data Quality & Source Integrity

* **Institutional Grade Source:** Sourced directly from **Authorized Market Data Vendors** (not scraped from retail broker APIs like Zerodha, Fyers, or Angel One).
* **Zero Missing Ticks / Gaps:** Avoids the dropped ticks, rate-limit gaps, and candle anomalies common in retail broker websocket feeds.
* **Complete Market Coverage:** Full exchange-level accuracy for backtesting high-frequency and multi-leg option strategies.
  
## 📊 Available Datasets

| Exchange & Segment | Data Granularity | Period Covered | Coverage / Scope | Format |
| :--- | :--- | :--- | :--- | :--- |
| **NSE F&O** | **1-Minute** (OHLCV) | Jan 2015 – Jun 2026 | All Stock & Index Futures + Options | CSV |
| **NSE F&O Tick Data** | **Tick-by-Tick** (Market Depth) | Jan 2021 – Dec 2025 | Order-book depth & execution ticks | CSV |
| **MCX F&O** | **1-Minute** (OHLCV) | Jan 2021 – Jun 2026 | Commodity Futures & Options | CSV |
| **BSE F&O** | **1-Minute** (OHLCV) | Jan 2023 – Jun 2026 | Equity & Index Derivatives | CSV |

---

## 📁 Free Sample Files

Download and verify the dataset structure before purchasing:

* 📥 **Download Sample Dataset for NSE JAN2026 Options (OneDrive):** [Click Here to Access Sample File](https://1drv.ms/u/c/dd47a0ff1f5743f9/IQCBQgm5hi-xT4JstYf_akSXAfZvzmj3WTgiAc31Uxud8Jk?e=RN6OwD)

---

## 📋 Data Schema Standard

### 1-Minute OHLCV Schema
```csv
timestamp, symbol, expiry_date, strike_price, option_type, open, high, low, close, volume, open_interest

## 📩 Inquiries

For full dataset access, pricing details, or custom date/symbol extractions, reach out via:

* 📧 **Email:** `yj712432@gmail.com`
* 💬 **Telegram:** user- '@Djjain21'
