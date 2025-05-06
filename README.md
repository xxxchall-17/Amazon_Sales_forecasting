## 📊 Time Series Forecasting of Amazon Sales

This project aims to perform time series forecasting on Amazon sales data using statistical and deep learning models. The end goal is to accurately predict future sales trends and visualize results using an interactive dashboard.

---

### 🧠 Models Used

* **ETS (Error-Trend-Seasonality)**
* **ARIMA (AutoRegressive Integrated Moving Average)**
* **SARIMA (Seasonal ARIMA)**
* **Prophet (by Facebook)**
* **LSTM (Long Short-Term Memory Neural Network)**

---

### 📁 Project Structure

```
📂 TimeSeries-Forecasting-Amazon-Sales/
│
├── TIMESERIES_PROJECT__ (1).ipynb     # Main Jupyter Notebook with analysis
├── TIMESERIES REPORT.docx             # Detailed report with findings
├── 📈 forecast_graphs/                # (Optional) Folder to save forecast plots
└── README.md                          # Project overview and instructions
```

---

### 🗃️ Dataset

* **Source**: Kaggle
* **Contents**: Daily/weekly/monthly sales data of Amazon over a specific period.

---

### ⚙️ How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/amazon-time-series-forecast.git
   cd amazon-time-series-forecast
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter Notebook:

   ```bash
   jupyter notebook
   ```


---

### 📈 Results

* Forecast accuracy compared across models using metrics like MAPE, RMSE, etc.
* Visual plots of actual vs predicted sales for each model.
* LSTM showed the most accurate long-term predictions (as per report analysis).

---

### 📌 Key Insights

* Seasonality and trends were detected in sales.
* Statistical models performed well short-term; LSTM worked better for longer forecasts.
* Streamlit was used to build a simple, interactive dashboard for visualization.

---

### 🧑‍💻 Contributors

*Aanchal Mittal
*Utkarsh Tripathi


