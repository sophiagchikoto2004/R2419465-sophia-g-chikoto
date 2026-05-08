# R2419465-sophia-g-chikoto
Time Series Assignment
# Project Overview
This project investigates the presence of a long-run equilibrium relationship between stock prices of Apple (AAPL) and Microsoft (MSFT) using cointegration techniques.
Financial time series are often non-stationary, making standard regression analysis unreliable. This project applies econometric methods to determine whether these series move together over time.

# Objectives
- Test for non-stationarity using the 'Augmented Dickey-Fuller (ADF)' test  
- Determine whether the series are cointegrated  
- Estimate the long-run equilibrium relationship  
- Build an 'Error Correction Model (ECM)'
- Interpret results for financial decision-making


The dataset contains daily closing stock prices for:
- Apple Inc. (AAPL)
- Microsoft Corporation (MSFT)

**Source:** Yahoo Finance  
**Frequency:** Daily  
**Period:** 2018–2025 

# Methods Used
1. Stationarity Testing
- Augmented Dickey-Fuller (ADF) test

2. Cointegration Testing
- Engle-Granger two-step method

3. Long-Run Model
- Ordinary Least Squares (OLS)

4. Short-Run Dynamics
- Error Correction Model (ECM)

# Key Findings
- Both AAPL and MSFT are non-stationary
- A cointegration relationship exists
- Residuals from regression are stationary
- The ECM shows adjustment toward equilibrium

# Limitations
- Does not account for volatility clustering  
- Sensitive to structural breaks (e.g., COVID-19)  
- Assumes a linear relationship  
- Excludes macroeconomic variables  

# Diagnostic Analysis
- Residual autocorrelation
- Model validation

# Model Weakness (Damage)
- Structural breaks
- Non-linearity

# Future Work (Directions)
- VECM
- Regime-switching models
