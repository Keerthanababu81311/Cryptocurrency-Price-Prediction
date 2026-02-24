# Cryptocurrency-Price-Prediction
A Streamlit-based Cryptocurrency Price Prediction app using LSTM (RNN) and TensorFlow to forecast crypto prices from historical market data.

# 📈 Cryptocurrency Price Prediction using LSTM (RNN)

A deep learning-based cryptocurrency price prediction web application built using **TensorFlow, LSTM (RNN), and Streamlit**.

This project forecasts cryptocurrency prices using historical market data from Yahoo Finance.

---

## 🚀 Live Features

✔ Select cryptocurrency (BTC, ETH, XRP, DOGE, SOL, etc.)  
✔ Choose custom date range  
✔ Train LSTM model dynamically  
✔ Predict future prices  
✔ Compare Real vs Predicted values  
✔ Visualize trading volume  

---

## 🧠 Model Architecture

The model is built using a **Recurrent Neural Network (RNN) with LSTM layers**:

- 4 LSTM layers (50, 60, 80, 120 units)
- Dropout layers for regularization
- Dense output layer
- Optimizer: Adam
- Loss Function: Mean Squared Error
- Sequence window: 60 timesteps

This allows the model to capture time-series dependencies in cryptocurrency price movement.

---

## 🛠️ Tech Stack

- **Frontend:** Streamlit
- **Data Source:** yFinance API
- **Libraries:** 
  - TensorFlow / Keras
  - Scikit-learn
  - NumPy
  - Pandas
  - Matplotlib
- **Model Type:** LSTM (Deep Learning)
- **Problem Type:** Time Series Forecasting

---

## 📊 How It Works

1. Fetch historical crypto data using yFinance
2. Scale data using MinMaxScaler
3. Create 60-day sliding window sequences
4. Train LSTM model
5. Predict future prices
6. Compare predicted vs actual values
7. Visualize results

---

## 📷 Output Visualization

- Real Price (Red Line)
- Predicted Price (Green Line)
- Trading Volume Chart

---

## ⚙️ Installation & Run

1. Clone the repository:
```bash
git clone https://github.com/your-username/crypto-price-prediction.git
