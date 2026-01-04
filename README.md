**Roadmap for algorithmic trading**

**Books under a module will be read concurrently**



Each Module will take 4 months to complete and you must spend 2 months after to work on trading algorithms/projects



**1.) Statistical Learning and Quantitative Trading Foundations**

* Statistics and Data Analysis for Financial Engineering by Ruppert
* Introduction to Statistical Learning by Hastie
* Successful Algorithmic Trading by Michael-Halls-Moore
* The Elements of Quantitative Investing by Giuseppe



**Skills I'll gain after completing:** You will be able to design, test, and evaluate basic systematic trading strategies using sound statistical reasoning, avoiding common pitfalls such as overfitting and data leakage. You will also understand how predictive models, portfolio construction, and risk considerations fit together in a practical quantitative trading workflow.



**Project:** Build a Research-Grade Backtesting Engine and Evaluate Simple Strategies Correctly

* Design and implement a vectorized backtesting framework from scratch that supports daily equities or ETF data, transaction costs, position sizing, and proper performance evaluation, then use it to compare several simple systematic strategies (momentum, mean reversion, and volatility-scaled trend following).



**2.) Time Series Modeling and Probabilistic Strategy Design**

* Applied Time Series Analysis and Forecasting with Python by Changquan Huang
* Bayesian Modeling and Computation in Python by Osvaldo A. Martin
* Advanced Algorithmic Trading by Michael-Halls-Moore
* Machine Learning in Finance by Dixon



**Project:** Walk-Forward Time-Series Strategy with Bayesian Uncertainty and Regime Sensitivity

* Develop a time-series-based trading strategy that explicitly models uncertainty(Dynamic Position sizing) using Bayesian methods (e.g., Bayesian regression or volatility estimation) and evaluate it using strict walk-forward validation across multiple market regimes.



**Skills I'll gain after completing:** You will be able to model financial time series under uncertainty, apply Bayesian methods to stabilize estimates and quantify risk, and engineer strategies that remain robust under changing market conditions. You will also be capable of running disciplined walk-forward experiments and translating research models into repeatable, production-ready trading systems.





**3.) Advanced Financial Machine Learning \& Decision Systems**

* Analysis of Financial Time Series by Ruel S. Tsay
* Machine Learning for Algorithmic Trading by Jansen
* Advances in Financial Machine Learning by Prado
* Foundations of Reinforcement Learning with Applications in Finance by Ashwin Rao



**Project:** Financial Machine Learning Strategy with Leakage-Safe Validation and Meta-Labeling

* Build a machine-learning-driven trading strategy using financial ML techniques (labeling, feature engineering, and meta-labeling) and validate it using purged cross-validation and realistic execution assumptions, then stress-test it across regime changes.



**Skills I'll gain after completing:** You will be able to apply advanced machine learning and reinforcement learning methods to trading problems while rigorously controlling for bias, non-stationarity, and execution effects. You will understand how to validate complex strategies in realistic market settings and distinguish genuinely robust signals from statistically convincing but economically meaningless results.



**4.) Final Capstone (4 Months):** Regime-Aware Capital Allocation System



**Goal:** Build and validate a system that reallocates capital across a fixed asset universe by inferring market regimes online and weighting existing signals probabilistically under strict, leakage-safe evaluation.



**What You Must Build**



**1. Regime Inference (Online, Causal):** Infer latent market regimes from time-series features such as volatility, trend strength, and correlations using unsupervised or Bayesian methods. All regime detection must be causal and operate without future information.



**2. Probabilistic Signal Weighting:** Use a small, fixed set of predefined trading signals and estimate their regime-conditional effectiveness. Signals must be combined using confidence-weighted exposures rather than binary trade decisions.



**3. Capital Allocation and Risk Control:** Translate probabilistic signal confidence into portfolio weights using volatility targeting, exposure limits, and drawdown-based throttling to control risk dynamically.



**4. Robust Validation:** Validate the full system using walk-forward testing, regime-conditioned performance analysis, and ablation studies comparing results with and without regime inference and probabilistic weighting.



