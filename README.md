# freqtrade_hyperliquid_download-data

This repository contains **downloaded market data** for the [Hyperliquid](https://hyperliquid.xyz) decentralized exchange, formatted and ready to be used with [Freqtrade](https://www.freqtrade.io).

It will progressively grow over the months.  
📅 **Data collection started:** 2025-04-01  
📊 **Includes:** All supported trading pairs and markets on Hyperliquid, meaning spot AND futures

---

## 📦 What’s Inside

- Historical OHLCV data from Hyperliquid
- Market pairs compatible with Freqtrade
- Data files organized by trading pair and time interval (e.g., `1m`, `5m`, etc.)
- Automatically updated via GitHub Actions

---

## 🔄 Usage with Freqtrade

This repository is meant to serve as the `--datadir` when running Freqtrade backtesting or hyperparameter optimization.

### ✅ Setup

1. **Clone this repository**:
   ```bash
   git clone https://github.com/frequenthippoOrg/freqtrade_hyperliquid_download-data.git
