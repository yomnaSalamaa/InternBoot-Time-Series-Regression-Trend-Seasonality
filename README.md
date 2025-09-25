**📈 Time Series Regression: Trend + Seasonality**

This project explores how to adapt regression models for time series forecasting by capturing both trend and seasonality in retail sales data. Along the way, I performed Exploratory Data Analysis (EDA) to understand the underlying sales dynamics.

The dataset comes from the 🛒 Store Sales – Time Series Forecasting competition
.

🎯 Objectives

Perform EDA to uncover sales patterns, seasonal effects, and holiday impacts

Extend regression to handle time-dependent patterns

Capture trend using polynomial features on a time index

Model seasonality with month, day-of-week, and holiday indicators

Compare extended regression vs. a baseline linear regression

🔍 Exploratory Data Analysis (EDA)
Data Checks

Verified missing values and overall data quality

Ensured correct data types for time-series analysis

Visual Insights

Sales trends across days, weeks, and months

Effects of promotions and holidays

Variations across stores and product families

🛠 Feature Engineering
Trend

Linear time index

Polynomial transformations

Seasonality

Month indicators

Day-of-week indicators

Holiday flags

Other Features

Lag features (past 7 & 30 days)

Rolling averages

On-promotion counts

📊 Tech Stack

Python 🐍

Pandas 🐼

Scikit-learn 🤖

Matplotlib 📉

🚀 Learning Outcomes

Applied EDA to reveal time-dependent patterns

Learned to engineer features specific to time series

Understood trend vs. seasonality in forecasting

Compared baseline vs. enhanced regression models

Improved skills in visualization and feature design
