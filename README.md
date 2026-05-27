# Modelling Nigeria's Inflation Rate Using ARIMA

## Overview
This project analyzes and models Nigeria’s monthly inflation rate using the Autoregressive Integrated Moving Average (ARIMA) model.

The study examines inflation trends between 2008 and 2023 and evaluates the performance of ARIMA models in capturing inflation dynamics.

Objectives
- Examine the trend and behavior of Nigeria’s inflation rate
- Fit an appropriate ARIMA model
- Evaluate model performance using statistical accuracy measures

Dataset
Source: National Bureau of Statistics (NBS), Nigeria

Data Frequency: Monthly

Period Covered: 2008 – 2023

Tools: R Programming . Microsoft Excel & word

---

## Methodology
The Box-Jenkins methodology was applied:

1. Exploratory Data Analysis
2. Stationarity Test (ADF Test)
3. ACF and PACF Analysis
4. ARIMA Model Identification
5. Model Estimation
6. Diagnostic Checking
7. Model Performance Evaluation

## Model Used

ARIMA(1,1,1)

Model Equation:

Yt = 0.786Y(t-1) - 0.592ε(t-1) + εt

Performance Metrics

| Metric | Value |
|---|---|
| RMSE | 0.723 |
| MAE | 0.472 |
| MAPE | 3.77% |

---

## Key Findings
- Nigeria’s inflation rate shows persistent fluctuations
- Inflation became stationary after first differencing
- ARIMA(1,1,1) provided the best model fit
- The model achieved high predictive accuracy

Future Improvements
- Implement ARIMAX models
- Compare with GARCH models
- Include external macroeconomic variables

Department of Statistics  
Federal University of Technology Minna# nigeria-inflation-arima-model
ModellingNigeria’s inflation rate using ARIMA model
