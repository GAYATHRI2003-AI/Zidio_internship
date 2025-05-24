# Zidio_internship

# 📈 Stock Market Time Series Forecasting

This project applies multiple time series forecasting techniques to historical stock market data to predict future stock prices. It includes preprocessing, visualization, modeling, and evaluation using classical statistical methods and deep learning.

---

## 🚀 Project Objectives

- Collect and preprocess historical stock market data
- Understand time series components: **trend**, **seasonality**, and **noise**
- Build and compare models: **ARIMA**, **SARIMA**, **Prophet**, and **LSTM**
- Visualize predictions and evaluate accuracy
- Present results with clear metrics

---

## 📁 Dataset

- **File**: `Historic_stock_data.csv`
- **Fields**: `Date`, `Open`, `High`, `Low`, `Close`, `Volume`, `Name`
- Focused column: `Close` (closing stock prices)
- Data frequency: Daily (converted to business days for modeling)

---

## 🛠️ Technologies Used

- **Language**: Python
- **Libraries**:
  - `pandas`, `numpy` – Data handling
  - `matplotlib`, `seaborn`, `plotly` – Visualization
  - `statsmodels` – ARIMA/SARIMA
  - `prophet` – Facebook Prophet model
  - `tensorflow/keras` – Deep learning (LSTM)
  - `sklearn` – Evaluation metrics

---

## 📊 Models Implemented

### 1. ARIMA
- Models linear relationships in stationary data.
- Parameters: (p=5, d=1, q=0)

### 2. SARIMA
- Extends ARIMA with seasonal components.
- Parameters: (1,1,1)(1,1,1,12)

### 3. Prophet
- Robust to outliers and missing data.
- Automatically detects trends and seasonality.

### 4. LSTM (Deep Learning)
- Captures complex nonlinear temporal patterns.
- Sequence length: 60 days, single-layer LSTM

---

## 📉 Evaluation Metrics

Each model is evaluated on a 30-day forecast using:

| Metric | Description |
|--------|-------------|
| **RMSE** | Root Mean Squared Error |
| **MAE**  | Mean Absolute Error |
| **MAPE** | Mean Absolute Percentage Error |

### ✅ Example Output Table:

| Model   | RMSE  | MAE   | MAPE (%) |
|---------|-------|-------|-----------|
| ARIMA   | 2.34  | 1.98  | 3.45%     |
| SARIMA  | 2.01  | 1.75  | 3.10%     |
| Prophet | 1.95  | 1.65  | 2.89%     |
| LSTM    | 1.60  | 1.38  | 2.20%     |

---

## 📈 Visualizations

- Time series decomposition (trend, seasonality, residual)
- Model forecasts overlaid on actual data
- LSTM vs actual values on test set
- Prophet trend and seasonal component plots

---

## 🧪 How to Run

1. Upload `Historic_stock_data.csv` to your Google Colab session.
2. Run the full Python script in a Google Colab notebook.
3. View plots and evaluation outputs.
4. Compare model performances to select the best forecasting method.

---

## 📚 Learning Outcomes

- Proficient in working with time series financial data
- Implemented both statistical and deep learning models
- Gained skills in model evaluation and forecasting
- Built an end-to-end forecasting pipeline

---

## 📌 Future Work

- Include multivariate modeling (Open, High, Low, Volume)
- Incorporate external events or news sentiment
- Deploy with Streamlit dashboard or Flask API

---

## 👨‍💻 Author

**Your Name**  
Email: gaya3devi.2003b@gmail.com 
LinkedIn: www.linkedin.com/in/gayathri-devi-b-  

---

## 📄 License

This project is licensed under the MIT License. See `LICENSE` for details.
Data Science
