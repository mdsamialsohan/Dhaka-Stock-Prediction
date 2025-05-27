# 📈 Stock Price Forecasting Using Machine Learning and Deep Learning (Dhaka Stock Exchange)

This project explores stock price forecasting using historical trading data from the **Dhaka Stock Exchange**, with a focus on three listed companies: **AMCL Pran**, **Bata Shoe**, and **Jamuna Oil**. A range of machine learning (ML) and deep learning (DL) models were applied and benchmarked to evaluate predictive performance across different time horizons.

---

## 🎯 Project Objectives

- Forecast stock prices using both **traditional ML** and **deep learning architectures**
- Compare model performance using RMSE across multiple time horizons (1 Day, 1 Week, 15 Days)
- Incorporate technical indicators (EMA, SMA-7, MACD) to enrich the feature set
- Propose and evaluate an **Ensemble Model** to improve prediction accuracy

---

## 📊 Datasets

- Real-world time series data from:
  - **AMCL Pran**
  - **Bata Shoe**
  - **Jamuna Oil**
- 10+ months of daily stock prices
- Preprocessing included missing value handling, feature engineering, and technical indicators

---

## 🧠 Models Used

### 🔹 Machine Learning Models
- Random Forest Regressor
- XGBoost Regressor

### 🔹 Deep Learning Models
- LSTM (Long Short-Term Memory)
- GRU (Gated Recurrent Unit)

### 🔹 Hybrid
- Ensemble Model (Weighted Averaging)

---

## 📈 Results Summary (RMSE)

| Dataset     | Prediction Length | Best Model      | RMSE    |
|-------------|--------------------|------------------|---------|
| AMCL Pran   | 15 Days            | **LSTM**         | 10.73   |
|             | 1 Day              | Random Forest    | 3.23    |
|             | 1 Week             | GRU              | 7.88    |
|             | Avg. Best          | **Ensemble**     | Lowest across all |
| Bata Shoe   | 15 Days            | XGBoost          | 15.08   |
|             | 1 Day              | Random Forest    | 7.31    |
|             | 1 Week             | XGBoost          | 13.84   |
|             | Avg. Best          | **Ensemble**     | Best overall |
| Jamuna Oil  | 15 Days            | Random Forest    | 3.37    |
|             | 1 Day              | XGBoost          | 1.13    |
|             | 1 Week             | XGBoost          | 2.87    |
|             | Avg. Best          | **Ensemble**     | RMSE = 1.07 |

---

## 📌 Key Takeaways

- **XGBoost** consistently outperformed other individual models across datasets.
- **LSTM** showed better performance for **long-term predictions**.
- **Random Forest** excelled at **short-term forecasts**, particularly for volatile data.
- The **Ensemble method** achieved the lowest average RMSE for all prediction lengths across all datasets.

---

## 🔧 Features & Technical Indicators

- **Basic features**: Open, Close, High, Low, Volume
- **Technical indicators**:
  - EMA (Exponential Moving Average)
  - SMA-7 (Simple Moving Average)
  - MACD (Moving Average Convergence Divergence)

---

## 📂 Project Structure

```📁 Dhaka-Stock-Prediction/
├── AMCL pran.ipynb
├── Bata.ipynb
├── JamunaOil.ipynb
├── Graph.ipynb
├── Data2/
│ ├── AMCL(PRAN)_data.csv
│ ├── BATASHOE_data.csv
│ └── JAMUNAOIL_data.csv
└── README.md
```

---

## 📊 Evaluation Metric

All models were evaluated using **RMSE (Root Mean Squared Error)** to measure prediction accuracy.

---

## 🧪 Future Work

- Incorporate external factors (e.g., market news sentiment)
- Apply attention-based deep learning models (Transformer)
- Test using different optimization techniques and hyperparameter tuning
- Real-time deployment with API integration

---

## 🙋‍♂️ Author

**MD Samial Hasan Sohan**  
MSc Data Analytics, University of Portsmouth  
📍 Based in London | Open to Data Science & ML Opportunities  
📫 Email: [samialsohan@gmail.com](mailto:samialsohan@gmail.com)  
🔗 LinkedIn: [linkedin.com/in/mdsamialsohan](https://www.linkedin.com/in/mdsamialsohan/)
🌐 Website: [samialsohan.com](https://www.samialsohan.com)

---

## 💼 Use Case

This repository demonstrates applied ML/DL knowledge for:
- **Time Series Forecasting**
- **Ensemble Learning**
- **Technical Indicator Analysis**
- **Real-World Stock Market Prediction**

It’s a great addition to my **data science portfolio**, especially for roles in fintech, trading, analytics, and business intelligence.

