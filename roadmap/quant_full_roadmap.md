
# Quant Developer Roadmap — Full 6-Month Study Plan (Expanded)
## Table of Contents
- [Month 1 — Math & Statistics](#month-1--math--statistics)
  - [Week 1 — Linear Algebra & Calculus](#week-1--linear-algebra--calculus)
  - [Week 2 — Probability & Statistics](#week-2--probability--statistics)
  - [Week 3 — Time Series Fundamentals](#week-3--time-series-fundamentals)
  - [Week 4 — Optimization & Numerical Methods](#week-4--optimization--numerical-methods)
- [Month 2 — Finance & Derivatives](#month-2--finance--derivatives)
- [Month 3 — Quant Modelling](#month-3--quant-modelling)
- [Month 4 — Engineering](#month-4--engineering)
- [Month 5 — ML & Alternative Data](#month-5--ml--alternative-data)
- [Month 6 — Interview Prep](#month-6--interview-prep)

---

# Month 1 — Math & Statistics

## Week 1 — Linear Algebra & Calculus
### Theory Topics
- Vectors, matrices, linear combinations  
- Matrix operations (multiply, transpose, inverse)  
- Determinants, geometric interpretation  
- Eigenvalues/eigenvectors  
- Derivatives, gradients, Jacobian/Hessian  

### Videos
- 3Blue1Brown — Essence of Linear Algebra  
  https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab  
- MIT OCW — 18.06 Linear Algebra  
  https://www.youtube.com/playlist?list=PL221E2BBF13BECF6C  
- Khan Academy — Multivariable Calculus  
  https://www.youtube.com/playlist?list=PLSQl0a2vh4HBqJYh9FHDN-yPjC2lXRYds  

### Coding Exercises
- Implement matrix multiplication manually  
- Compute eigenvalues manually + via NumPy  
- Visualize linear transforms on point clouds  

---

## Week 2 — Probability & Statistics
### Theory Topics
- PDFs, PMFs  
- Expectation, variance  
- Covariance, correlation  
- Bayes theorem  
- LLN, CLT  
- Hypothesis testing  

### Videos
- Harvard STAT110  
  https://www.youtube.com/playlist?list=PL2SOU6wwxB0uwwH80KTQ6ht6KhgqyJZIx  

### Coding Exercises
- Simulate distributions  
- Demonstrate LLN/CLT  
- Hypothesis testing  

## Week 3 — Time Series Fundamentals
### Theory Topics
- Stationarity and unit roots  
- Random walks  
- AR, MA, ARMA, ARIMA  
- ACF / PACF  
- Rolling statistics  
- Residual diagnostics  

### Videos
- Stationarity Intuition  
  https://www.youtube.com/watch?v=YLY8ca0o5Y4  
- ARIMA Tutorial  
  https://www.youtube.com/watch?v=rn4ht-0s-MY  

### Coding Exercises
- Load OHLCV data, compute log returns  
- ADF stationarity test  
- Fit AR(1), ARIMA  
- Plot residual ACF/PACF  

---

## Week 4 — Optimization & Numerical Methods
### Theory Topics
- Gradient descent  
- Newton’s Method  
- Numerical integration  
- Constrained optimization  
- Monte Carlo simulation  

### Videos
- Gradient Descent (StatQuest)  
  https://www.youtube.com/watch?v=sDv4f4s2SB8  
- Newton’s Method  
  https://www.youtube.com/watch?v=pTnEG_WGd2Q  

### Coding Exercises
- Gradient descent on quadratic function  
- Portfolio optimization with scipy.optimize  
- Monte Carlo estimation of π  
- Newton's root finding implementation  

---

# Month 2 — Finance & Derivatives

## Week 5 — Financial Instruments & Bonds
### Theory Topics
- Asset classes  
- Bond pricing  
- Duration & Convexity  
- Yield curve bootstrapping  

### Videos
- Bionic Turtle — Duration  
  https://www.youtube.com/watch?v=Ay4JA9h6Wl8  
- MIT Yield Curve  
  https://www.youtube.com/watch?v=u7Y7fG9G8lU  

### Coding Exercises
- Price coupon & zero-coupon bonds  
- Compute duration & convexity  
- Build simplified yield curve  

---

## Week 6 — Derivatives Fundamentals
### Theory Topics
- Forwards & futures  
- Swaps  
- Call/put mechanics  
- Arbitrage pricing  
- Put-call parity  

### Videos
- Forwards/Futures Explained  
  https://www.youtube.com/watch?v=vU3fQ7eFGRc  
- Put-Call Parity  
  https://www.youtube.com/watch?v=-wEsJqwo1go  

### Coding Exercises
- Call/put payoff diagrams  
- Verify put–call parity using real market data  

---

## Week 7 — Option Pricing & Greeks
### Theory Topics
- Black–Scholes  
- Greeks (Δ, Γ, Θ, Vega, ρ)  
- Binomial tree pricing  

### Videos
- Black-Scholes Explained  
  https://www.youtube.com/watch?v=I6iq5Y7sXP8  

### Coding Exercises
- Implement BS manually  
- Compute analytic Greeks  
- Compute finite-difference Greeks  
- Build CRR binomial tree  

---

## Week 8 — Backtesting, Simulation & VaR
### Theory Topics
- Look-ahead bias  
- Survivorship bias  
- Slippage & transaction cost modeling  
- Sharpe, Sortino, Drawdown  
- Historical / Parametric / MC VaR  

### Videos
- Backtesting Basics  
  https://www.youtube.com/watch?v=xfzGZB4HhEE  
- VaR Overview  
  https://www.youtube.com/watch?v=zfF2GBrE234  

### Coding Exercises
- Moving average crossover backtest  
- Compute Sharpe/Sortino/Drawdown  
- Compute VaR via 3 methods  


# Month 3 — Quant Modelling

## Week 9 — Stochastic Processes
### Theory Topics
- Brownian Motion (BM)
- Geometric Brownian Motion (GBM)
- Ito’s Lemma (conceptual understanding)
- Ornstein–Uhlenbeck (OU) mean-reversion process

### Videos
- GBM Explained  
  https://www.youtube.com/watch?v=OgO1gpXSUzU  
- Ito’s Lemma Intuition  
  https://www.youtube.com/watch?v=1gG6jvYzy84  

### Coding Exercises
- Simulate GBM using Euler–Maruyama  
- Simulate OU process and estimate parameters  
- Monte Carlo option pricing and compare vs Black–Scholes  

---

## Week 10 — Volatility Modelling
### Theory Topics
- ARCH/GARCH models
- EWMA volatility
- Realized vs Implied Volatility
- Volatility clustering

### Videos
- GARCH Modelling Tutorial  
  https://www.youtube.com/watch?v=Vfo5le26IhY  

### Coding Exercises
- Fit GARCH(1,1) using Python’s arch package  
- Forecast volatility for next N days  
- Compute EWMA volatility  
- Compare realized vs implied volatility  

---

## Week 11 — Portfolio Optimization & Risk
### Theory Topics
- Efficient frontier
- Portfolio variance and covariance estimation
- Value at Risk (VaR)
- Conditional VaR (CVaR)
- Stress testing and scenario analysis

### Coding Exercises
- Compute efficient frontier for multi-asset portfolio  
- Compute portfolio VaR (historical/parametric/MC)  
- Compute CVaR  
- Perform stress tests  

---

## Week 12 — Market Microstructure
### Theory Topics
- Market/Limit orders
- Order book structure
- Bid–ask spread, liquidity, slippage
- Execution algorithms: VWAP/TWAP

### Videos
- Limit Order Book Basics  
  https://www.youtube.com/watch?v=SCXnU6N38VA  

### Coding Exercises
- Implement a limit order book simulator  
- Implement VWAP and TWAP execution strategies  
- Add transaction cost model to backtest  

---

# Month 4 — Engineering

## Week 13 — Data Engineering for Quant Systems
### Theory Topics
- Data pipelines (batch/streaming)
- SQL schema design for time-series
- ETL processes
- Data validation & quality checks

### Videos
- SQL for Data Analysts  
  https://www.youtube.com/watch?v=HXV3zeQKqGY  

### Coding Exercises
- Create OHLCV database schema (Postgres/TimescaleDB)  
- Build ETL pipeline to ingest and validate daily data  
- Compute rolling metrics from DB queries  

---

## Week 14 — Performance Optimization
### Theory Topics
- Profiling (cProfile, line_profiler)
- Vectorization (NumPy)
- JIT compilation (Numba)
- Caching & memoization
- Parallelism (multiprocessing)

### Videos
- Numba Speedup Tutorial  
  https://www.youtube.com/watch?v=1AwG0T4gaO0  

### Coding Exercises
- Profile your backtester  
- Optimize slow loops with vectorization  
- Apply numba JIT to hot paths  
- Write PyTest unit tests for core functions  

---

## Week 15 — APIs & Deployment
### Theory Topics
- REST API design
- FastAPI architecture
- Docker basics
- Cloud deployment (AWS/GCP/Azure)

### Videos
- FastAPI Intro  
  https://www.youtube.com/watch?v=0RSb6d0gE3g  
- Docker for Python  
  https://www.youtube.com/watch?v=SnSH8Ht5cL4  

### Coding Exercises
- Build `/backtest/run` API endpoint  
- Build `/pricing/bs` option pricing API endpoint  
- Dockerize the application  
- Test API locally with HTTP client  

---

## Week 16 — End-to-End Quant Project
### Project Goals
- Pick a strategy (momentum, mean reversion, volatility)
- Build data pipeline
- Build backtest engine
- Implement risk metrics (vol, VaR, Sharpe)
- Optionally deploy via FastAPI

### Deliverables
- Clean project repo with README
- Code modules + tests
- Plots and analysis notebook
- Optional local Docker deployment

---

# Month 5 — Machine Learning & Alternative Data

## Week 17 — ML for Finance
### Theory Topics
- Supervised Learning (Classification/Regression)
- Feature engineering for financial data
- Cross-validation for time series
- Avoiding data leakage
- Model performance metrics

### Videos
- Sentdex – ML for Finance  
  https://www.youtube.com/watch?v=Z4I8dHdlkGQ  
- Walk-Forward Validation  
  https://www.youtube.com/watch?v=58iW1uUfOYU  

### Coding Exercises
- Build return-direction classifier  
- Engineer features: momentum, volatility, volume  
- Evaluate precision/recall and Sharpe of predictions  
- Implement walk-forward validation  

---

## Week 18 — Alternative Data
### Theory Topics
- Sentiment analysis (text → score)
- News-based signals
- Volume & flow-based features

### Coding Exercises
- Scrape/download news headlines  
- Compute sentiment using VADER or transformer models  
- Merge sentiment with returns  
- Correlation & predictive power study  

---

## Week 19 — System Architecture (Quant Engineering)
### Theory Topics
- Event-driven architecture
- Asynchronous processing
- Latency & throughput basics
- Real-time data streaming simulation

### Videos
- Event-Driven Architecture  
  https://www.youtube.com/watch?v=KGRTZp5c3i0  

### Coding Exercises
- Build async data feed simulator  
- Build event-driven signal engine  
- Measure per-event processing latency  

---

## Week 20 — Project Polish
### Tasks
- Refactor project code structure
- Improve tests  
- Optimize bottlenecks  
- Create high-quality README  
- Add plots and visualizations  
- Prepare a PDF report summarizing your project  

---

# Month 6 — Interview Prep

## Week 21 — Data Structures & Algorithms
### Theory Topics
- Arrays, sliding window, two pointers  
- Hash maps, sets  
- Heaps, priority queues  
- Trees & graphs  
- Dynamic programming  
- Complexity (Big-O)

### Coding Exercises
- Solve 40–50 LeetCode medium problems  
- Focus on time-series-like questions: sliding window, stacks  
- Implement matching engine / order book problem  

---

## Week 22 — Domain Deep Dive
Choose one specialization:
- Fixed Income  
- Volatility (VIX, implied vol surfaces)  
- Market Microstructure  
- Options EXOTICS (barriers, Asians)

### Coding Exercises
- Implement swap pricer  
- Build implied volatility surface visualizer  
- Build order book depth imbalance indicator  

---

## Week 23 — Mock Interviews
### Tasks
- Review math, stats, finance fundamentals  
- Practice explaining your project in 60 seconds  
- Prepare answers for common quant dev questions  
- Do mock technical + system design round  

---

## Week 24 — Final Resume, Portfolio & Applications
### Tasks
- Polish resume for quant roles  
- Add project writeups to GitHub  
- Write concise LinkedIn summary  
- Apply to 5–10 quant dev roles  
- Start networking messages on LinkedIn  

---

# End of Roadmap
