# 🚀 Phase B (Weeks 15–28) March: Building & Connecting the System

---

## **Weeks 15–16: Backtesting Engine (MVP)**

- **Goal**: Build a simulator that takes your ML model and tests it on historical OHLCV data.
    
- **What you’ll learn**:
    
    - Event-driven architecture (price comes in → model decides → trade placed).
        
    - Order simulation (buy/sell, position tracking, PnL calculation).
        
    - Transaction costs (commissions, slippage).
        
- **Deliverable**: Run your first backtest with a toy ML model and get a performance curve (equity curve).
    

👉 This makes the project **real**: you’ll see if your model makes or loses money.

---

## **Weeks 17–18: Feature Engineering for Trading**

- **Goal**: Expand the input data your models can “see.”
    
- **What you’ll learn**:
    
    - Return calculations (log returns, rolling returns).
        
    - Volatility measures (std dev, ATR, Bollinger bands).
        
    - Volume-based features (OBV, volume delta).
        
    - Lagged features (price change t-1, t-2, …).
        
- **Deliverable**: Create a feature set with 20–50 features and use it in backtests.
    

👉 This is where models start having _predictive power_.

---

## **Weeks 19–20: Advanced ML Models**

- **Goal**: Upgrade from scikit-learn toys to deeper models.
    
- **What you’ll learn**:
    
    - Random forests & XGBoost (strong tabular models).
        
    - Shallow neural networks in PyTorch/TensorFlow.
        
    - Training/validation splits specific to time-series (no random shuffle).
        
- **Deliverable**: Compare tree-based vs NN-based models on your backtest framework.
    

👉 You’ll now see which types of models handle financial data better.

---

## **Weeks 21–22: Risk Management Layer**

- **Goal**: Stop thinking only in “accuracy” and start thinking in **risk-adjusted return**.
    
- **What you’ll learn**:
    
    - Position sizing: Kelly criterion, fixed fraction, capped risk per trade.
        
    - Portfolio-level metrics: Sharpe ratio, Sortino, max drawdown.
        
    - Daily stop-loss limits & exposure caps.
        
- **Deliverable**: Modify backtest to apply a risk rule (e.g., max 40% capital at risk).
    

👉 This is survival training — without this, even a good model goes broke.

---

## **Weeks 23–24: Live Data Pipeline**

- **Goal**: Move from static CSVs to live market data feeds.
    
- **What you’ll learn**:
    
    - Exchange APIs (Binance, Alpaca, Interactive Brokers).
        
    - WebSockets for streaming OHLCV in real time.
        
    - Caching & resampling live ticks into 1m/5m candles.
        
- **Deliverable**: A script that pulls live crypto/stock prices and updates your Pandas dataframe in real time.
    

👉 Now your AI can breathe “real market air.”

---

## **Weeks 25–26: Live Trading Simulator**

- **Goal**: Connect your backtester + data feed = paper-trading bot.
    
- **What you’ll learn**:
    
    - Trade execution via API (placing test orders).
        
    - Syncing account balances & positions.
        
    - Logging trades in a database for review.
        
- **Deliverable**: Run a full-day paper trading session with logs of every trade.
    

👉 Your AI will now act in real markets — with fake money.

---

## **Weeks 27–28: Evaluation & Debug**

- **Goal**: Test robustness and prepare for real deployment.
    
- **What you’ll learn**:
    
    - Walk-forward testing (train → test → retrain).
        
    - Monte Carlo resampling on trades (to test variance).
        
    - Stress-testing with bad data or extreme volatility.
        
- **Deliverable**: A performance report showing whether the system can be trusted.
    

👉 This is your **go/no-go checkpoint** before ever risking €1 of real capital.

---

# 🧠 What You’ll Know After Phase B

By the end of Week 28 (~7 months total project time):  
✅ Build and test a trading strategy end-to-end.  
✅ Engineer features that make ML models “see” patterns.  
✅ Train & compare multiple ML models for market prediction.  
✅ Manage risk so your AI doesn’t blow up the account.  
✅ Stream real data from an exchange.  
✅ Run a **paper trading bot** that mimics a live trading system.  
✅ Evaluate robustness with proper financial metrics.