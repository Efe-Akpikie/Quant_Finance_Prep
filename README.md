# Statistical Finance & Financial Machine Learning  
## A Research-First, Implementation-Driven Quantitative Trading Sequence

---

## Program Philosophy

This five-course sequence is designed to train **professional-grade quantitative researchers and system builders**, not retail traders.

The curriculum follows a deliberate progression:

**Statistical validity → system realism → time-series & portfolio theory → market structure → financial machine learning**

Throughout the program:
- Research discipline is prioritized over backtest performance
- Economic plausibility precedes model construction
- Portfolio-level risk dominates single-signal optimization
- Every result must survive adversarial statistical scrutiny

**Format:** Research + implementation  
**Duration:** ~24–27 months  
**Outcome:** Buy-side–ready quant research capability

---

## Course 1 — Statistical Inference & Predictive Modeling for Financial Data  
**Duration:** 5 months

### Primary Texts
- *Statistics and Data Analysis for Financial Engineering* — Ruppert & Matteson  
- *An Introduction to Statistical Learning* — James, Witten, Hastie, Tibshirani  
- *Quantitative Trading Strategies Using Python* — Liu Peng
- *Successful Algorithmic Trading* — Michael Halls-Moore

### Scope
- Probability theory for financial data
- Estimation, inference, and uncertainty
- Linear and nonlinear predictive models
- Bias–variance tradeoff in noisy markets
- Hypothesis testing under data-snooping risk

### Course Capstone — Research Paper
**Title:**  
**Statistical Validity of Simple Trading Signals**

**Deliverables**
- 8–12 page research paper
- Explicit hypotheses and null models
- Multiple-testing and overfitting analysis
- Statistical vs economic significance
- Reproducible code appendix

**Skill Outcome**
Ability to **invalidate weak strategies statistically before engineering them**.

---

## Course 2 — Algorithmic Trading Systems & Backtesting Under Realistic Constraints  
**Duration:** ~5 months

### Primary Texts  
- *Advanced Algorithmic Trading* — Michael Halls-Moore  
- *Machine Learning for Algorithmic Trading* — Stefan Jansen
- *An Introduction to Market Microstructure Theory* — Andreas Krause
- *Building Winning Algorithmic Trading Systems: A Trader's Journey From Data Mining to Monte Carlo Simulation to Live Trading* - Kevin J. Davey

### Scope
- Event-driven trading architectures
- Look-ahead bias and data leakage
- Slippage, spreads, and market impact
- Walk-forward and rolling evaluation
- Portfolio-level accounting and PnL attribution

### Course Capstone — Implementation Project
**Title:**  
**High-Performance Event-Driven Backtesting & Execution System**

**Deliverables**
- Multi-asset **event-driven** backtesting and execution engine  
- Order, fill, and execution simulation with transaction cost & slippage models  
- Walk-forward and rolling evaluation suitable for ML training and validation  
- Portfolio-level accounting, attribution, and diagnostics  

**Implementation Constraints**
- Core engine in **C/C++** for performance and low latency  
- **Python-first API** for strategy logic and ML model integration  
- Optimized data flow to support repeated model retraining and evaluation  

**Skill Outcome**
Understanding **how execution realism, costs, and system design invalidate naïve ML backtests**.

---

## Course 3 — Financial Time Series & Risk-Aware Portfolio Optimization  
**Duration:** ~6 months

### Primary Texts
- *Analysis of Financial Time Series* — Ruey S. Tsay  
- *Portfolio Optimization: Theory and Application* — Daniel P. Palomar  
- *The Elements of Quantitative Investing* — Giuseppe Paleologo
- *Financial Markets Theory* — Barucci & Fontana  

### Scope
- Time-series dynamics (ARMA, GARCH, regimes)
- Volatility forecasting and clustering
- Estimation error and turnover
- Constrained portfolio optimization
- Drawdowns, tail risk, and stress testing

### Course Capstone — Research + Implementation
**Title:**  
**Volatility-Aware Portfolio Construction Under Estimation Error**

**Deliverables**
- 12–15 page research paper
- Time-series volatility models
- Constraint-aware optimization engine
- Stress tests vs classical benchmarks

**Skill Outcome**
Transition from **signal-centric thinking to capital allocation and risk control**.

---

## Course 4 — Financial Machine Learning & Alpha Validation  
**Duration:** ~5 months

### Primary Texts
- *The Elements of Statistical Learning* — Friedman, Hastie, Tibshirani  
- *Foundations of Reinforcement Learning with Applications in Finance* — Rao & Jelvis  
- *Machine Learning in Finance* — Dixon, Halperin, Bilokon
- *Advances in Financial Machine Learning* — Marcos López de Prado   

### Scope
- High-dimensional feature spaces
- Regularization and ensemble methods
- Financial labeling and meta-labeling
- Purged and embargoed cross-validation
- Multiple-testing correction and robustness

### Course Capstone — Research-Grade Study
**Title:**  
**Robust Alpha Discovery Under Multiple-Testing Constraints**

**Deliverables**
- 15–20 page research paper
- Hypothesis-driven feature engineering
- Purged CV and out-of-sample validation
- Explicit failure and fragility analysis

**Skill Outcome**
Capacity to perform **professional-grade ML research without self-deception**.

---

## Final Program Capstone — Institutional-Grade Quant Research & System Build  
**Duration:** ~3 months

### Title
**End-to-End Systematic Strategy: From Economic Hypothesis to Risk-Controlled Deployment**

### Required Integration
- Economic rationale (Course 4)
- Statistical rigor (Course 1)
- System realism (Course 2)
- Portfolio & risk modeling (Course 3)
- Machine learning hygiene (Course 5)

### Deliverables
- 20–30 page buy-side-quality research paper
- Fully reproducible research + trading codebase
- Detailed post-mortem explaining why the strategy may fail

### Completion Standard
Graduates are aligned with:
- Buy-side quant research expectations
- Prop-trading system design standards
- Institutional risk and governance discipline

---

## Final Note

This program is intentionally demanding.

Its purpose is not to teach **how to trade**, but to teach **how to think like a quantitative researcher who understands why most strategies fail before capital is ever deployed**.
