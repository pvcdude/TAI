
# 📚 Phase A (Weeks 1–14) December: What You’ll Learn

sources for everything: [3 Months ML](https://www.youtube.com/watch?v=qNxrPri1V0I)

### **Weeks 1–2: Python + Data Handling**

- **Python syntax deep dive**: loops, functions, classes, imports.
    
- **Numpy basics**: vectors, arrays, matrix ops (you’ll need this for math-heavy parts).
    
- **Pandas basics**: reading CSVs, selecting columns, resampling time-series data.
    
- **Deliverable**: Load OHLCV (Open, High, Low, Close, Volume) data into Pandas, plot a candlestick chart.

👉 You’ll learn: _how to handle raw financial data in code_.

---

### **Weeks 3–4: Statistics & Probability**

- [Khan Academy](https://www.khanacademy.org/math/statistics-probability)
	
- **Core stats**: mean, median, variance, standard deviation.
    
- **Probability distributions**: normal, lognormal, Bernoulli (coin flips), binomial.
    
- **Random variables**: generating random returns and simulating “fake” markets.
    
- **Central Limit Theorem**: why many returns look normal-ish.
    
- **Deliverable**: Write a script that simulates random coin-flip trading and plots cumulative returns.

👉 You’ll learn: _the language of risk & randomness — critical for trading_.

---

### **Weeks 5–6: Data Analysis & Indicators**

- **Rolling windows**: moving averages, rolling variance.
    
- **Technical indicators** (your acronyms from earlier):
    
    - **EMA**: Exponential Moving Average
        
    - **RSI**: Relative Strength Index
        
    - **MACD**: Moving Average Convergence Divergence
        
- **Correlation**: how assets move together.
    
- **Deliverable**: Calculate EMA, RSI, and MACD from OHLCV data and visualize them.
    

👉 You’ll learn: _the exact tools traders use daily to analyze charts_.

---

### **Week 7: Calculus Refresher (light)**

- **Derivatives**: slope → rate of change of price.
    
- **Integrals**: area under curve → cumulative returns.
    
- **Optimization basics**: finding maxima/minima.
    
- **Deliverable**: Implement gradient descent in Python on a toy dataset.
    

👉 You’ll learn: _the math for how ML models update weights_.

---

### **Weeks 8–9: Linear Algebra Essentials**

- **Vectors & matrices**: representation of multiple signals.
    
- **Dot products**: weighting multiple indicators.
    
- **Eigenvalues/eigenvectors**: why PCA (dimensionality reduction) works.
    
- **Deliverable**: Code PCA on a small dataset, reduce 10 features to 2.
    

👉 You’ll learn: _how ML compresses and transforms data_.

---

### **Weeks 10–11: Algorithms & ML Fundamentals**

- **Regression**: linear and logistic regression.
    
- **Decision trees**: splitting rules → how models make “if/else” choices.
    
- **Ensemble models**: random forests, boosting.
    
- **Support Vector Machines (SVMs)**: separating classes.
    
- **Neural networks (intro)**: perceptrons, activation functions.
    
- **Deliverable**: Train a classifier to predict “up vs down” next day from indicators.
    

👉 You’ll learn: _the first models that can actually trade on past data_.

---

### **Weeks 12–13: ML with Scikit-Learn**

- **Scikit-learn**: using its API for models (fit, predict).
    
- **Toy datasets**: Iris, digits → practice pipeline building.
    
- **Cross-validation**: testing models properly.
    
- **Hyperparameter tuning**: adjusting knobs to improve results.
    
- **Deliverable**: Run a model pipeline with cross-validation and report accuracy.
    

👉 You’ll learn: _to stop overfitting and test ML correctly_.

---

### **Week 14: Data Cleaning & EDA**

- **EDA (Exploratory Data Analysis)**: summarizing and visualizing datasets.
    
- **Data cleaning**: handling missing candles, outliers, misaligned timestamps.
    
- **Feature engineering**: create new features (e.g., price returns, volatility).
    
- **Deliverable**: Clean a real crypto dataset and prepare it for ML.
    

👉 You’ll learn: _to make your raw messy market data usable by models_.

---

# 🔑 End of Phase A — What You Can Do

By Week 14, you’ll be able to:  
✅ Load & clean financial data (OHLCV).  
✅ Compute technical indicators and visualize them.  
✅ Understand randomness, variance, and probability of returns.  
✅ Use calculus & linear algebra to “get” how models work inside.  
✅ Train simple ML models (regression, trees, SVMs, intro neural nets).  
✅ Run and test ML models using scikit-learn.  
✅ Build cleaned, ready-to-train datasets for trading.