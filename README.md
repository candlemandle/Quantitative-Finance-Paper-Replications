# Quantitative Finance: Research Paper Replications

This repository is a personal collection of deep dives into various quantitative finance and financial engineering research papers. My goal is to bridge the gap between academic theory and practical implementation by replicating complex models and analyzing their behavior under different market conditions.

## Projects Overview

### 01. Forecasting Prices with Hidden Liquidity
* **Focus:** Market Microstructure & Order Book Dynamics.
* **Implementation:** Replicated the diffusion model by *Avellaneda, Reedy & Stoikov (2012)* to predict short-term price movements using Level-I quotes.
* **Key Assets:** Analyzed high-frequency data for AAPL, AMZN, and MSFT.

### 02. Risk-Aware Multi-Armed Bandits
* **Focus:** Machine Learning in Portfolio Optimization.
* **Implementation:** Based on *Huo & Fu (2017)*. Explored UCB1 and CVaR-based strategies to balance reward exploration and risk mitigation.
* **Highlights:** MST-based asset selection and performance backtesting during high-volatility regimes (including COVID-19 data).

### 03. Pricing Autocallables (ABRC)
* **Focus:** Exotic Derivatives & Model Risk.
* **Implementation:** A comparative study of Local Volatility (Black-Scholes) vs. Stochastic Volatility (Heston) for pricing Autocallable Barrier Reverse Convertibles (based on *Farkas et al., 2021*).
* **Analysis:** Sensitivity analysis of coupon barriers and maturity on model-risk discrepancies.

### 04. Market Dynamics & Tipping Points
* **Focus:** Non-linear dynamics in financial systems.
* **Implementation:** Analytical and numerical study of tipping points and stability in market processes.

## 🛠 Tech Stack
* **Language:** Python
* **Libraries:** NumPy, Pandas, Matplotlib, Scipy, Scikit-learn
* **Environment:** Jupyter Notebooks / Google Colab

---
*Disclaimer: These implementations are for educational and research purposes only.*
