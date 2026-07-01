# Data Analysis 2 - Assignment 1

Notebook analysis of the gender wage gap using the U.S. Census Bureau CPS earnings dataset.

## Project Goal

The assignment studies both unconditional and conditional gender wage gaps. It starts with a simple comparison between women and men, then adds controls to understand how the estimated gap changes once education, age, occupation, race, citizenship, marital status, and job characteristics are included.

## Files

- `da2_assignment1_artyom-ashigov.ipynb` - full Python notebook with cleaning, modeling, visualizations, and interpretation.
- `artyom_ashigov_gender_gap_analysis.pdf` - exported write-up/report.

## Methods

The notebook uses regression models to estimate wage gaps across different specifications. It compares standard and heteroskedasticity-robust standard errors, models education effects, and tests polynomial age terms to capture nonlinear age-earnings patterns.

## Main Analysis

- Estimates the unconditional gender wage gap for web developers.
- Studies how the gap changes with education controls.
- Compares age, age-squared, and higher-order polynomial terms.
- Extends the model with demographic and job-related controls.
- Interprets coefficients and confidence intervals for each model.

## Key Findings

- Female web developers earn about 18% less than male web developers in the unconditional model.
- Education and age explain part of the gap, but do not remove it.
- Polynomial age terms better capture the age-earnings relationship than a simple linear model.
- Additional controls reduce the estimated gap, but a statistically significant difference remains.

## Tools

Python, pandas, seaborn, plotnine, and statsmodels.
