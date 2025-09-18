# 🧭 Finance Lead Duties (Pre-ML Integration)

## **Phase 1: Consolidation (Weeks 7–10)**

- **Goal:** Translate market knowledge → structured “what data do we need and why.”
    
- Tasks:
    
    1. **Refine Finance 101** → build a shared doc for the team (like lecture notes but custom).
        
    2. **Market Scouting** → pick the first target market (stocks, crypto, forex).
        
        - Check data availability (is there free API?).
            
        - Look at liquidity, volatility, trading hours.
            
    3. **Indicator Primer** → write 1-page explainers for 2–3 key indicators (EMA, RSI, MACD).
        
        - Not code yet, just formulas + why they matter.
            

⏱️ Time: 3–4 hrs/week.  
📤 Output: Document → “First Market + Indicators to Watch.”

---

## **Phase 2: Data Collection Blueprint (Weeks 11–14)**

- **Goal:** Decide how to collect and organize trading data.
    
- Tasks:
    
    1. **Define Data Needs**: OHLCV candles (open, high, low, close, volume), maybe news sentiment.
        
    2. **Pick API Sources** (Yahoo Finance, Alpha Vantage, Binance, Polygon.io, etc).
        
    3. **Draft Schema**: What columns should each row of data have?
        
        - Example: `timestamp | open | high | low | close | volume`.
            
    4. **Basic Manual Collection**: Pull 1 week of daily prices manually (CSV). Share with group so programmers can test cleaning.
        

⏱️ Time: 4–6 hrs/week.  
📤 Output: A “Data Spec Document” + one small demo dataset.

---

## **Phase 3: Risk & Strategy Basics (Weeks 15–20)**

- **Goal:** Define trading constraints before AI touches anything.
    
- Tasks:
    
    1. **Risk Rules**:
        
        - Max % of pool per trade (e.g., 2–3%).
            
        - Stop-loss rules.
            
        - Max drawdown tolerated.
            
    2. **Strategy Skeletons**:
        
        - Momentum trading (trend following).
            
        - Mean reversion.
            
        - Simple moving average crossover.
            
    3. **Toy Backtests**:
        
        - Use Excel or Google Sheets to simulate 10 trades with these strategies.
            
        - Doesn’t matter if primitive — goal is intuition.
            

⏱️ Time: 5–8 hrs/week.  
📤 Output: Risk Rules Doc + Toy Strategy Report.

---

## **Hand-off to ML Programmers (Week ~21+)**

- By the time ML integration starts:
    
    - Finance lead delivers →
        
        1. Market chosen.
            
        2. Clean data spec + source.
            
        3. Rules of engagement (risk %).
            
        4. Strategy skeletons.
            

Then programmers can map models to _realistic finance behaviors_, not random.

---

👉 So in short:  
The **finance lead** is the “translator” between raw markets and the AI.  
They don’t stop programming entirely, but **40–50% of their time shifts to finance work** from week 7 onward, so by the time ML arrives, the AI isn’t trained in a vacuum.