📈 Sales Forecasting Using Machine Learning

Author: Devansh
Project Type: Machine Learning – Time Series Forecasting (Task 1)

🔍 About This Project

This project was created by Devansh as part of Machine Learning Task 1.

The goal of this project is to predict future sales using historical sales data.
It uses a machine learning model called Facebook Prophet, which is commonly used for time-series forecasting.

The project also exports results in a format that can be easily used in Power BI for building dashboards.

🎯 What This Project Does

Loads historical sales data

Cleans and prepares the data

Trains a forecasting model

Predicts future sales

Shows trends and seasonality

Exports results for Power BI visualization

🛠️ Tools Used

Python – Programming language

Pandas & NumPy – Data handling

Facebook Prophet – Sales forecasting

Scikit-learn – Error calculation

Matplotlib – Graphs and plots

Power BI – Dashboard visualization

VS Code – Code editor

📁 Dataset Used

File name: sales_data.csv

Type: Monthly sales data

Created and structured by Devansh

Columns:

date → Date of sales

sales → Sales value

The dataset is simple and beginner-friendly but realistic enough to show trends.

⚙️ How the Project Works (Steps)

Read sales data from CSV

Convert data into Prophet format

Train the forecasting model

Predict future sales values

Evaluate the model using MAE and RMSE

Save results as CSV files for Power BI

Plot sales trends and forecasts

📊 Output Files

After running the code, these files are created:

File Name	Description
sales_actuals.csv	Original sales data
sales_forecast.csv	Predicted future sales
sales_combined.csv	Actual vs Forecast (used in Power BI)
