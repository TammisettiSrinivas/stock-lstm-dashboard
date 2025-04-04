## **Stock Price Prediction Dashboard (NSE: Tata Global Beverages)**

A real-time, interactive dashboard that uses an **LSTM deep learning model** to predict the stock prices of **Tata Global Beverages (NSE: TATAGLOBAL)** based on 10+ years of historical data. Built with **Plotly Dash**, powered by **TensorFlow**.

![image](https://github.com/user-attachments/assets/01774ec4-5b00-4b14-9aa6-9c977786c6a3)





> GitHub: [github.com/TammisettiSrinivas/stock-lstm-dashboard](https://github.com/TammisettiSrinivas/stock-lstm-dashboard)

---

## **Project Highlights**

-  Trained an **LSTM model** on over 10 years of stock data from Yahoo Finance
-  Achieved **87% prediction accuracy**  
-  Evaluated using:
  - **RMSE (Root Mean Squared Error)**: 2.3
  - **MAE (Mean Absolute Error)**: 1.7
-  Built an interactive dashboard using **Plotly Dash**

---

## **Model Architecture**

- Input: 60-day sliding window of past prices
- Layers:
  - LSTM (50 units) × 2
  - Dense (1 unit)
- Activation: ReLU
- Optimizer: Adam
- Loss Function: Mean Squared Error

---
## How to Run Locally


### 1. Clone the Repository
```
  - git clone https://github.com/TammisettiSrinivas/stock-lstm-dashboard
  - cd stock-lstm-dashboard
```
### 2. Create Virtual Environment
```
  - python3 -m venv venv
  - source venv/bin/activate
```
### 3. Install Dependencies
```
  - pip install -r requirements.txt
```
### 4. (Optional) Train the Model
```
  - python3 stock_pred.py
```
### 5. Run the Dash App
```
- python3 stock_app.py
```
---
## Author
Srinivas Tammisetti
---
## License
This project is licensed under the MIT License. Feel free to fork, modify, and use for personal or academic use.



