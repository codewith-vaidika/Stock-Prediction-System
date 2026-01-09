

#  Stock Price Prediction Model

A **Machine Learning project (2024 – Present)** that predicts stock prices using **time-series data**. The project implements **LSTM networks** for sequential prediction, **XGBoost** for regression-based forecasting, and a custom **Ensemble model (XGBoost + LSTM)** to combine the strengths of both approaches.

---

## 🚀 Features

*  **Data Preprocessing** using Pandas & NumPy
*  **Visualization** with Matplotlib for trend analysis
*  **LSTM (Long Short-Term Memory)** for sequential time-series prediction
*  **XGBoost (Extreme Gradient Boosting)** for regression-based forecasting
*  **Ensemble Model** (LSTM + XGBoost) for improved accuracy
*  Modular, extensible Python code

---

##  Tech Stack

* **Programming Language:** Python
* **Libraries & Tools:**

  * `scikit-learn` – Preprocessing, evaluation
  * `xgboost` – Gradient boosting regression
  * `tensorflow / keras` – LSTM implementation
  * `pandas`, `numpy` – Data handling
  * `matplotlib` – Visualization

---

##  Models Implemented

1. **LSTM Model** – Captures sequential dependencies in stock prices.
2. **XGBoost Model** – Learns regression patterns efficiently.
3. **Ensemble Model** – Combines LSTM & XGBoost predictions (ensemble learning).

---

##  Project Structure

```bash
Stock-Price-Prediction/
│── data/                # Stock market datasets
│── notebooks/           # Jupyter notebooks for experimentation
│── src/                 # Source code (models, preprocessing, utils)
│   ├── preprocessing.py
│   ├── lstm_model.py
│   ├── xgboost_model.py
│   ├── ensemble_model.py
│── results/             # Predictions, plots, evaluation metrics
│── requirements.txt     # Python dependencies
│── README.md            # Project documentation
```

---

##  Installation & Usage

1. Clone the repository

   ```bash
   git clone https://github.com/your-username/Stock-Price-Prediction.git
   cd Stock-Price-Prediction
   ```

2. Install dependencies

   ```bash
   pip install -r requirements.txt
   ```

3. Run training script (example)

   ```bash
   python src/ensemble_model.py
   ```

---

## 📈 Results

* LSTM captures long-term stock trends.
* XGBoost performs well on short-term fluctuations.
* **Ensemble model outperforms individual models** by combining sequential + regression strengths.
