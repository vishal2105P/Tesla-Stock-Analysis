# Tesla-Stock-Analysis


This project performs time series analysis and prediction of Tesla's stock prices using machine learning models. It uses historical data to generate features, visualize trends, and evaluate the performance of multiple regression algorithms.

## 📁 Dataset
The dataset used is `TESLA.csv` which includes:
- Date
- Open, High, Low, Close, Adj Close
- Volume

## 📊 Features Created
- Time-based: Year, Month, Day, DayOfWeek
- Technical Indicators: MA7, MA30, MA90 (Moving Averages)
- Price & Volume Change (%)
- Volatility (30-day rolling std)

## 🧠 Models Used
- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

## 🚀 How to Run
Clone the repository.
Ensure TESLA.csv is in the root directory.
Run the notebook stock_analysis_tesla.ipynb in Jupyter or Google Colab.

## 📌 Output
Model evaluation metrics (R², RMSE, MAE)
Graphical insights
Prediction plots for each model

## 📈 Visualizations
- Stock price trends with moving averages
- Trading volume
- Correlation heatmap
