Time Series Regression (Trend + Seasonality)

This project demonstrates how to adapt regression models for time series forecasting by capturing both trend and seasonality patterns in sales data. It also includes Exploratory Data Analysis (EDA) to better understand sales dynamics before modeling.

The dataset comes from the Store Sales – Time Series Forecasting competition
, containing several years of daily sales data from multiple stores and product families.

🔹 Objective

Explore sales data to uncover patterns, seasonality, and holiday effects.

Extend regression beyond static predictors to handle time-based dynamics.

Capture trend using polynomial features on a time index.

Capture seasonality using month, day-of-week, and holiday effects.

Compare the extended regression model with a simple baseline linear regression.

🔹 Exploratory Data Analysis (EDA)

Checked for missing values and data consistency.

Visualized sales distributions across stores and product families.

Analyzed daily, weekly, and monthly sales patterns.

Explored the impact of promotions and holidays on sales.

🔹 Features for Modeling

Trend Features: Linear & polynomial time index.

Seasonality Features: Month, day-of-week, and holiday indicators.

Holiday Effects: Incorporated using external holiday dataset.

Model Comparison: Baseline vs. regression with trend + seasonality.

Visualization: Actual vs. predicted sales over time (monthly averages).

🔹 Tech Stack

Python

Pandas

Scikit-learn

Matplotlib

🔹 Learning Outcomes

Learn how to engineer time-aware features for regression.

Understand the difference between trend and seasonality in time series.

Apply EDA techniques to uncover time-dependent sales patterns.

Build skills in time series preprocessing, feature engineering, and visualization.
