📊 Stock Trend Prediction with XGBoost

This project predicts stock price trends (Up/Down) using machine learning (XGBoost).
It uses historical stock price data (downloaded via yFinance), applies feature engineering, trains an ML model, and visualizes results in a bar chart.

🚀 Project Workflow

Data Collection

Download stock data (e.g., Apple – AAPL) using yFinance.

Feature Engineering

Daily return (% change).

Moving Averages (5-day, 10-day).

Target: 1 if next day Close > today Close else 0.

Model Training

Train-test split (time-based, no shuffling).

Model: XGBoost Classifier.

Evaluation

Accuracy score.

Bar chart comparison of Actual vs Predicted trends.

📌 Tech Stack

Python

Pandas, NumPy – data handling

yFinance – stock data API

XGBoost – ML model

Matplotlib – visualization

📊 Example Output

Accuracy printed in console

Bar Chart showing:

🔵 Blue bars = Actual trend (Up/Down)

🔴 Red bars = Predicted trend
