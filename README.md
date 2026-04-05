# 📈 Apple Stock Price Forecasting using LSTM

## 📌 Overview
This project predicts the **opening stock price of Apple Inc.** using a **Long Short-Term Memory (LSTM)** neural network.

It uses historical stock data (2015–2020) and forecasts the next day's opening price based on previous values.

---

## 🎯 Objectives
- Perform time series forecasting
- Build an LSTM-based deep learning model
- Evaluate prediction performance

---

## 🧠 Tech Stack
- Python
- pandas, numpy
- matplotlib
- scikit-learn
- keras (TensorFlow)

---

## 📂 Dataset
- Apple stock data (2015–2020)
- Features include: open, close, high, low, volume
- Only **open price** is used in this project

---

## ⚙️ Preprocessing
- Removed unnecessary columns
- Converted date to datetime and set as index
- Scaled data using MinMaxScaler
- Converted time series → supervised learning format

---

## 🏗️ Model
- 2 LSTM layers (200 units each)
- Dropout (0.2)
- Dense output layer

**Loss:** MAE  
**Optimizer:** Adam  
**Epochs:** 50  
**Batch size:** 72  

---

## 📊 Results
- RMSE: 9.783  
- MAE: 6.667  

The model captures overall trends but struggles with sharp price changes.

---

## 📈 Output
- Compares predicted vs actual opening prices
- Visualization using matplotlib

---

## 🚀 Improvements
- Use more time steps (window size > 1)
- Add more features (volume, close, etc.)
- Hyperparameter tuning
- Try GRU or Transformer models

---

## 👤 Author
Georgios Stratidis
