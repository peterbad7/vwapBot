# Elite VWAP Trading Bot for MT5

created by Ahmed or ug.k_

A sophisticated algorithmic trading bot that uses Volume-Weighted Average Price (VWAP) with machine learning confirmation to trade forex and commodities.

## ✨ Key Features

1. **Advanced VWAP Strategy**
   - 3D VWAP calculation with volume profile
   - Future VWAP prediction using linear regression
   - Dynamic deviation thresholds

2. **Smart Risk Management**
   - ATR-based position sizing
   - Volatility-adjusted stop loss/take profit
   - Account balance protection (auto-liquidation prevention)

3. **Multi-Timeframe Analysis**
   - Automatic timeframe selection
   - Works on M15 by default (configurable)

4. **Machine Learning Integration**
   - Optional ML confirmation of signals
   - Pre-trained model included

5. **Real-Time Dashboard**
   - Interactive price charts with VWAP
   - Positions monitoring
   - Performance metrics

6. **Alert Systems**
   - Telegram notifications
   - Trade execution alerts
   - Error notifications

## 📊 Supported Instruments
- Forex (EURUSD, etc.)
- Commodities (XAUUSD)
- Cryptocurrencies (BTCUSD)

## ⚙️ Installation
1. Install Python 3.8+
2. Install requirements:
   ```bash
   pip install -r requirements.txt
