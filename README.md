# Lithium, Uranium and Tech : A Quantitative Dive into ETF Time Series

- KWEB — KraneShares CSI China Internet ETF  
- LIT — Global X Lithium & Battery Tech ETF  
- URA — Global X Uranium ETF

## Objectives

- Conduct a time series analysis of three sector-specific ETFs over a 10-year horizon.
- Evaluate price dynamics, log-returns, and distributional properties.
- Test for stationarity and assess short-term dynamics using ARIMA models.
- Investigate long-term equilibrium relationships using the Engle–Granger cointegration test.

## Methods & Models

**Descriptive Analysis**
- Weekly log-returns
- Mean, standard deviation
- Skewness, kurtosis
- Histogram & QQ-plots
- Correlation matrix
- ACF (Autocorrelation Function)

**Univariate Time Series Modeling**
- ARIMA(6,1,0) estimation per ETF
- Residual diagnostics
- Impulse Response Functions (IRF)

**Stationarity Testing**
- Augmented Dickey-Fuller (ADF)
- KPSS Test

**Cointegration Analysis**
- Engle–Granger 2-step test (KWEB vs LIT)

## Data

- Source: Yahoo Finance  
- Frequency: Weekly  
- Period: January 2015 — January 2025

## Tool

- Python (Jupyter Notebook)  
- Report written in LaTeX

## Key Findings

- All three ETFs exhibit non-normal return distributions with excess kurtosis and skewness.
- ARIMA models showed no statistically significant autoregressive lags at the 5% level.
- Shocks observed in log-prices tend to dissipate rapidly (low persistence).
- ADF and KPSS tests confirm non-stationarity of log-price series.
- No cointegration found between KWEB and LIT, suggesting no long-term equilibrium relationship.

---

**Thank you for exploring this project. I am continuously learning and developing my quantitative finance skills, and I welcome all feedback, suggestions, or ideas for improvement.**

**Gianni Marchetti**    
📧 giannimarchetti@outlook.fr
