# 📈 Stock Price Predictor (LSTM-Based)

A deep learning model that predicts stock prices using **LSTM (Long Short-Term Memory)** networks. It fetches historical stock data from Yahoo Finance (NSE: National Stock Exchange - India), trains an LSTM model, and forecasts future trends. The project also visualizes predictions and evaluates performance with multiple metrics.

---

## 🚀 Features

- ✅ Real-time stock data fetching via **`yfinance`**
- ✅ Data normalization using **MinMaxScaler**
- ✅ Deep learning model using **LSTM (Keras)**
- ✅ Forecasts next **180 days** of stock prices
- ✅ Visualizes:
  - Actual stock prices
  - Train/Test predictions
  - Future predictions with trend annotation
- ✅ Computes:
  - MSE (Mean Squared Error)
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)
  - R² Score

---

## 🗂️ Project Structure

📦StockPricePrediction  
├── pridiction using lstm.ipynb # Main script for training and prediction  
├── README.md # Documentation (you are here)  


---

## 💻 How to Run

### ✅ Prerequisites

Ensure Python 3.x is installed, then install dependencies:

```bash
pip install numpy pandas matplotlib yfinance scikit-learn tensorflow
```

## 🧑‍💻 Author

* **Priyanshu Mittal**
* **Jiya Agrawal**

## 📜 License

This project is licensed under the MIT License.

---
