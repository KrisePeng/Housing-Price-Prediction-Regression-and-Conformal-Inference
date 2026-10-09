# Housing Price Prediction and Conformal Inference

**STAT/Q SCI 403 Final Project | University of Washington**  
**Author:** Yan Peng | June 2025

## Overview

This project explores housing price prediction and uncertainty quantification using King County housing data. The analysis combines multiple linear regression, bootstrap inference, penalized regression, and Jackknife+ conformal prediction.

## Methods

- **Regression:** Multiple linear regression with feature transformations, residual diagnostics, and Ridge/Lasso comparisons.
- **Statistical Inference:** 95% Gaussian and bootstrap confidence intervals using 1,000 bootstrap replications.
- **Conformal Prediction:** Jackknife+ implemented from scratch to construct prediction intervals using leave-one-out residuals.

## Key Results

The final regression model achieved an adjusted R² of **0.6552**. Gaussian and bootstrap confidence intervals were broadly consistent. Jackknife+ produced prediction intervals with a mean width of approximately **$1.20 million**, highlighting substantial predictive uncertainty.

## Files

- [Final Report](Stat403-Project.pdf)
- [R Markdown Code](code.Rmd)
