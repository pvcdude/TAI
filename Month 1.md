# 📅 Month 1 – Programming (September)

---

## **Weeks 1–2: Python + Data Handling**

### **Core Topics**

1. **Python Syntax Deep Dive**
    
    - Variables, loops (`for`, `while`), conditionals (`if/else`).
        
    - Functions → arguments, return values.
        
    - Classes → define a class, use `__init__`, store state, call methods.
        
    - Imports → using standard libraries (`math`, `datetime`) and external packages.
        
2. **NumPy Basics**
    
    - Arrays vs Python lists (speed + vectorization).
        
    - Array indexing/slicing.
        
    - Element-wise operations.
        
    - Linear algebra: dot products, norms, transposes.
        
    - Random number generation (`np.random`).
        
3. **Pandas Basics**
    
    - DataFrames and Series.
        
    - Reading CSV files (`pd.read_csv`).
        
    - Selecting columns and rows (`.loc`, `.iloc`).
        
    - Basic cleaning (handling missing values).
        
    - Resampling → convert 1-min data into daily averages.
        
4. **Visualization Basics**
    
    - `matplotlib.pyplot` → line plots, histograms.
        
    - Intro to `mplfinance` (candlestick plotting library).
        

---

### **Practical Work**

- Install Python + Jupyter Notebook (or VSCode).
    
- Practice exercises:
    
    - Write a function to calculate factorial iteratively + recursively.
        
    - Use NumPy to simulate 1000 coin flips, count heads.
        
    - Load a CSV of fake stock data into Pandas.
        
    - Resample hourly → daily closing price.
        
- **Deliverable:** Load OHLCV (Open, High, Low, Close, Volume) data into Pandas and plot your first candlestick chart.
    

👉 **Skill learned:** _turning raw financial data into something you can see and manipulate._

---

## **Weeks 3–4: Statistics & Probability**

### **Core Topics**
0. [Khan Academy](https://www.khanacademy.org/math/statistics-probability)
	
1. **Descriptive Statistics**
    
    - Mean, median, mode.
        
    - Variance, standard deviation.
        
    - Skewness and kurtosis (why markets are “fat-tailed”).
        
2. **Probability Distributions**
    
    - Normal distribution → Gaussian bell curve.
        
    - Lognormal → used in modeling stock prices.
        
    - Bernoulli → single coin flip.
        
    - Binomial → repeated coin flips.
        
    - Uniform → random picks with equal chance.
        
3. **Random Variables**
    
    - Generate synthetic returns using `numpy.random.normal`.
        
    - Simulate multiple traders flipping coins.
        
    - Monte Carlo basics (repeat many random runs).
        
4. **Central Limit Theorem**
    
    - Why sums of independent random variables look normal.
        
    - Demo: simulate rolling dice → plot average distribution.

---

### **Practical Work**

- Write Python functions:
    
    - Compute mean, variance manually (without NumPy).
        
    - Then re-do with NumPy → compare speed.
        
    - Simulate 1000 days of stock returns using `np.random.normal`.
        
    - Plot histogram of returns.
        
    - Simulate coin-flip trading (heads = +1%, tails = –1%).
        
    - Plot cumulative returns curve over time.
        
- **Deliverable:** A script that simulates random coin-flip trading and plots cumulative returns.
    

👉 **Skill learned:** _you’ll be speaking the “language of risk & randomness,” which is the backbone of trading and backtesting._

---

## **Why This Matters**

- **Weeks 1–2** = You get your “hands dirty” with real price data → you won’t be scared of CSVs or APIs later.
    
- **Weeks 3–4** = You build an **intuition for randomness, risk, and variance**, which trading models must respect.
    

---

⚡ By the end of September you should:

- Read OHLCV data in Python.
    
- Plot candlesticks + line charts.
    
- Write code that simulates toy “markets.”
    
- Understand how randomness → risk.