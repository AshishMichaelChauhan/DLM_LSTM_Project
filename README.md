
# 📈 LSTM-Based Stock Price Prediction: NIFTY 50 and Nestle India Ltd.

## 🚀 **Project Overview**
This project uses a **Long Short-Term Memory (LSTM)** deep learning model to predict the stock prices of **NIFTY 50** and **Nestle India Ltd.** based on historical daily stock market data. The objective is to evaluate how accurately the LSTM model can forecast future stock prices and analyze the correlation between Nestle and NIFTY 50.

## 🎯 **Objective**
- Predict future stock prices with high accuracy using LSTM.
- Analyze the correlation between **NIFTY 50** and **Nestle India Ltd.** stock movements.
- Assess the model's ability to capture stock market trends.

## 🔥 **Problem Statement**
Predicting stock prices is a complex time series challenge due to market volatility. This project tackles the difficulty of capturing intricate patterns using LSTM while evaluating the influence of large-cap stocks (Nestle India Ltd.) on the NIFTY 50 index.

## ⚙️ **Technologies Used**
- **Python**: Data processing, model building, and visualization
- **Libraries:** TensorFlow, Keras, Pandas, NumPy, Matplotlib, yfinance
- **Jupyter Notebook:** For model development and visualization
- **Data Source:** Yahoo Finance

## 🛠️ **Project Structure**
```
/data
    └── nifty_50.csv
    └── nestle_india.csv
/model
    └── lstm_model.h5
/visualizations
    └── plots and comparison graphs
LSTM_Stock_Price_Prediction.ipynb
README.md
```

## 🔧 **Model Architecture**
- **Input Layer:** 60 time steps (past 60 days) with 1 feature (closing price).
- **LSTM Layers:** 3 layers with 50 units each.
- **Dropout:** 20% dropout to prevent overfitting.
- **Dense Layers:** 25 units with ReLU activation and a final Dense layer with 1 unit for prediction.
- **Optimizer:** Adam with learning rate = 0.001.
- **Loss Function:** Mean Squared Error (MSE).

## 📊 **Results and Insights**
- The model effectively captures **trends in both NIFTY 50 and Nestle India Ltd.**, but shows some underestimation during high volatility.
- **Strong correlation** between Nestle India and NIFTY 50 movements, especially post-2017.
- **Investment Insight:** Nestle acts as a **defensive stock**, offering stability during market downturns.

## 📈 **Usage**
1. Clone the repository:
```
git clone <repo_link>
```
2. Install dependencies:
```
pip install -r requirements.txt
```
3. Run the Jupyter notebook to train and evaluate the model.

## 🚀 **Future Enhancements**
- Add external factors (volume, sentiment, economic indicators) to improve accuracy.
- Use Transformer-based models for better performance.
- Integrate real-time stock data for live predictions.

---
✅ **Contributors:**  
- **Ashish Michael Chauhan (055007)**  
- **FORE School of Management, PGDM Big Data Analytics**
