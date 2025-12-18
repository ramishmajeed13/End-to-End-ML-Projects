# End-to-End-ML-Projects

*A collection of mini-projects exploring Classification (Financial) and Regression (Real Estate).*

## Project 1: US Recession Prediction (Binary Classification)
**Goal:** Predict economic recessions using historical interest rate data.
- **Tech Stack:** Python, Pandas, Scikit-Learn (Random Forest).
- **Key Insight:** Interest rates alone are a weak predictor of recessions. The model highlighted the need for multi-variate data (GDP, Unemployment) to capture complex economic downturns.
- **Result:** Built a functional pipeline dealing with time-series data and custom target engineering.

## Project 2: California Housing Price Prediction (Regression)
**Goal:** Predict median house values based on location, income, and age.
- **Model Comparison:**
    - *Linear Regression:* $R^2$ Score = 0.57 (Underfitted)
    - *Random Forest:* $R^2$ Score = 0.80 (Best Performer)
- **Key Insight:** The relationship between income and housing price is non-linear. The Random Forest model captured spatial patterns (clustering around the coast) that the linear model missed.
- **Visuals:** See the `notebooks` folder for heatmaps and "Actual vs Predicted" plots.

---
*Author: Ramish Majeed*
