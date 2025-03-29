Walmart Sales Demand Forecasting using Linear Regression

Project Overview

Sales demand forecasting is a critical process that enables businesses to optimize inventory, pricing strategies, and supply chain management. This project utilizes Linear Regression to predict Walmart's future sales based on historical trends.

Objective
The goal of this project is to develop a data-driven approach to forecast sales demand using historical data and key influencing factors such as time, seasonality, and day of the week.

Dataset & Features
Historical Sales Data: Past sales trends over different time periods.
Independent Variables (X):
Month, Day, and Day of the Week – Captures seasonality and shopping patterns.
Promotions & Discounts (if available) – Measures the impact of marketing strategies.
Dependent Variable (Y): Sales (units sold).
Methodology: Steps in Forecasting
1. Data Collection & Preprocessing

Extracted historical sales data from Walmart records.
Cleaned and prepared the dataset by handling missing values and normalizing variables.
2. Model Training: Linear Regression

Developed a linear regression model to find relationships between sales and influencing factors.
Equation used:
Sales
=
m
X
+
c
Sales=mX+c
where m represents the slope (rate of sales change), and c is the intercept (baseline sales).
3. Sales Forecasting Example

For April 20 (Month = 4, Day = 20, Day of Week = 2), the predicted sales using our model:

Sales
=
(
15.2
∗
4
)
+
(
7.5
∗
20
)
+
(
5.3
∗
2
)
+
100
=
321.4
Sales=(15.2∗4)+(7.5∗20)+(5.3∗2)+100=321.4
Thus, the expected sales on April 20 are approximately 321 units.

4. Model Evaluation & Accuracy

Used Mean Squared Error (MSE) and R² Score to assess model performance.
Identified patterns in seasonal demand fluctuations.
Key Findings & Business Impact
✔ Optimized Inventory Management: Prevents overstocking and understocking.
✔ Data-Driven Pricing Strategies: Helps adjust prices based on demand trends.
✔ Better Financial Planning: Supports forecasting for revenue and budgeting decisions.

Forecasted Sales for Key Dates

📊 March 15: 1,035,792 units
📊 April 20: 1,041,030 units
📊 May 25: 1,026,152 units

Technologies Used
Python (Pandas, NumPy, Matplotlib, Scikit-learn)
Linear Regression Model
Data Visualization (Seaborn, Matplotlib)
Future Enhancements
🔹 Incorporate additional factors like holiday effects, promotions, and weather conditions to improve accuracy.
🔹 Experiment with Time Series Forecasting (ARIMA, LSTM) for more advanced predictions.
🔹 Develop an interactive dashboard for real-time sales monitoring.

