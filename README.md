# stock-price-prediction
This project applies LSTM (Long Short-Term Memory) and Linear Regression models to predict stock prices of companies like Tesla (TSLA) and Google (GOOGL) using historical closing price data. The models are built using Python, Keras, and scikit-learn libraries, providing both future predictions and performance evaluations with visualizations.

# 📈 Stock Price Prediction Using LSTM and Linear Regression

This project demonstrates time series forecasting of stock prices using two approaches:

- **Long Short-Term Memory (LSTM)**: A type of Recurrent Neural Network (RNN) suitable for time series forecasting.
- **Linear Regression (LR)**: A classical ML model for trend prediction.

The models are trained on historical closing prices for **Tesla (TSLA)** and **Google (GOOGL)** stocks.

---

## 📁 Files in the Repository

- `tesla_stock_prediction.py` – Predicts Tesla stock prices using LSTM and Linear Regression.
- `google_stock_prediction.py` – Predicts Google stock prices using the same methods.

---

## 🧠 Technologies Used

- Python 🐍
- Pandas & NumPy – Data manipulation
- Matplotlib – Visualization
- scikit-learn – Preprocessing, Linear Regression, evaluation metrics
- TensorFlow & Keras – LSTM deep learning model

---

## 📊 Features

- Preprocesses historical stock data (`.csv`)
- Scales data using MinMaxScaler
- Creates look-back sequences for LSTM
- Trains LSTM and Linear Regression models
- Compares models using metrics:
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)
  - R² Score
- Predicts future stock prices
- Visualizes actual vs predicted prices

---

## 🚗 Tesla Stock Predictions

### 🔷 LSTM vs Actual Tesla Prices
LSTM Model Performance:
- RMSE: 15.310882195373841
- MAE: 10.262521419466847
- R²: 0.9966097164850514
- LSTM Predicted Future Price: 991.7583618164062
<img width="1123" alt="Screenshot 2025-05-26 at 10 01 32 PM" src="https://github.com/user-attachments/assets/77c6066d-5549-487c-bb2c-75d36605c589" />

### 🔶 Linear Regression vs Actual Tesla Prices
Linear Regression Model Performance:
- RMSE: 177.20871632592605
- MAE: 125.19323648227834
- R²: 0.4280574151980643
<img width="1136" alt="Screenshot 2025-05-26 at 10 01 14 PM" src="https://github.com/user-attachments/assets/8213b9d5-1ef5-4fb7-8ae4-32a12440432c" />

---

## 🔍 Google Stock Predictions

### 🔷 LSTM vs Actual Google Prices
LSTM Model Performance:
- RMSE: 4.202916906289386
- MAE: 3.6607123528837273
- R²: 0.7353606103298167
- LSTM Predicted Future Price: 125.4801025390625
<img width="1125" alt="Screenshot 2025-05-26 at 10 02 40 PM" src="https://github.com/user-attachments/assets/7e7cf54a-711a-43db-97e3-443b16d78892" />

### 🔶 Linear Regression vs Actual Google Prices
Linear Regression Model Performance:
- RMSE: 4.460313532140936
- MAE: 3.7101835365524294
- R²: 0.527828372618768
<img width="1151" alt="Screenshot 2025-05-26 at 10 02 47 PM" src="https://github.com/user-attachments/assets/4e3f6eb9-73f2-4213-88ae-e05d934a1422" />


---

## 📦 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sreemayi-25/stock-price-prediction.git
   cd stock-price-prediction

