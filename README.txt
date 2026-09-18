ASTRA PHONE v4
================

This is a phone-first PWA for paper trading.

WHAT'S NEW
- BTC, ETH, SOL, BNB, XRP and ADA
- Real 1-hour public market data
- Trend, RSI, momentum, volume, volatility and support/resistance analysis
- Explainable BUY/SELL/HOLD signal with strength
- Open/close paper positions
- Simulated P/L, equity, wins/losses and win rate
- Trade history stored locally on the device
- Risk-per-trade setting
- Notification permission + test notification
- Service worker foundation for future push alerts
- 192px/512px app icons

IMPORTANT
- PAPER TRADING ONLY. No real orders are placed.
- No exchange API keys are required.
- GitHub Pages is public: never put API keys or private secrets in this repository.
- Background push alerts while the app is fully closed require a push server. This build includes the service-worker foundation and local notification testing.

INSTALL
1. Replace your existing index.html with this version.
2. Upload manifest.json, sw.js, icon-192.png and icon-512.png.
3. Commit to the main branch.
4. Wait 1–2 minutes and refresh the GitHub Pages URL.
5. If Chrome shows an install/add-to-home-screen option, you can add Astra to your phone.

MARKET DATA
Astra reads public Binance Spot market data. The simulator does not authenticate or place orders.
