# 📈 Stock Price Prediction using Linear Regression

This project uses historical stock market data to **predict the next day's closing price** using a **Linear Regression model**. The dataset is fetched live using the `yfinance` library.

---

## 🧠 Objective

Predict the next closing price of a selected stock (e.g., Apple, Tesla) based on:

- Open
- High
- Low
- Volume

---

## 🛠️ Tools & Libraries

- Python
- [yfinance](https://pypi.org/project/yfinance/)
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

---

## 📊 Dataset

- Fetched using `yfinance` (Yahoo Finance)
- Stock used: **(e.g., Apple - AAPL)**  
- Features used: `Open`, `High`, `Low`, `Volume`
- Target: `Close` (next day)

---

## 🔍 Model

- **Algorithm**: Linear Regression
- **Evaluation Metric**: Root Mean Squared Error (RMSE)
- **RMSE Achieved**: `3.11`

---

## 📉 Results

A comparison of actual vs predicted stock closing prices was plotted using `matplotlib`.

---

## 🧪 How to Run

1. Install dependencies:
   ```bash
   pip install yfinance scikit-learn pandas matplotlib
