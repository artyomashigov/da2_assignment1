# Data Analysis 2 - Assignment 1

Notebook analysis of the gender wage gap using the U.S. Census Bureau Current Population Survey earnings dataset.

## Project Overview

This assignment investigates conditional and unconditional gender wage gaps. The notebook starts with a focused comparison among web developers, then extends the analysis to office and administrative support occupations to study how education, age, and other covariates affect estimated wage differences.

The work is written as a full analysis notebook: data selection, exploratory plots, regression models, coefficient interpretation, robustness checks, and a short causal discussion.

## Research Questions

- What is the unconditional gender wage gap in the selected occupation groups?
- How does the estimated gap change after accounting for education?
- How does the wage gap vary over the life course when age and gender-age interactions are included?
- Do polynomial age terms improve the explanation of earnings patterns?
- How much of the observed wage gap remains after adding demographic and job-related controls?

## Dataset and Scope

The analysis uses CPS earnings data and focuses on two occupational groups:

- Web developers
- Office and administrative support occupations

The notebook creates variables for hourly wages, log hourly wages, gender, age terms, and additional controls used in the extended regressions.

## Notebook Structure

- Overview of the wage-gap question and dataset
- Occupation filtering and sample description
- Visualization of hourly earnings and log earnings
- Baseline regressions for the unconditional gap
- Education-based conditional wage-gap models
- Age and polynomial age models
- Gender-by-age interaction analysis
- Extended regressions with additional controls
- Interpretation of statistical significance and confidence intervals
- Discussion of possible causal interpretation limits

## Methods

The notebook uses OLS regression with both standard and heteroskedasticity-robust standard errors. It also uses polynomial age specifications and interaction terms to study whether the gender wage gap changes across age.

## Key Findings

- In the web developer sample, the unconditional model estimates that female web developers earn about 18% less than male web developers.
- The gap remains meaningful after education controls are added.
- Age has a nonlinear relationship with wages, and polynomial age specifications fit the relationship better than a simple linear model.
- The gender wage gap changes over the life cycle, becoming larger after early career stages in the modeled office-worker sample.
- Additional controls reduce but do not fully eliminate the estimated gap.

## Files

- `da2_assignment1_artyom-ashigov.ipynb` - full notebook with code, plots, regressions, and interpretation.
- `artyom_ashigov_gender_gap_analysis.pdf` - exported report.

## Tools

Python, pandas, numpy, seaborn, matplotlib, plotnine, scipy, statsmodels, and stargazer.
