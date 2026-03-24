# 📈 AI Stock Prediction System

A production-ready **AI-powered stock prediction and trading system** built using deep learning and quantitative finance techniques.
This project focuses on predicting stock movements using time-series data and generating actionable trading signals.

---

## Features

* **Multi-stock prediction pipeline**
* **Sequence modeling (LSTM / extensible to Transformers)**
* **Optimized feature engineering (technical indicators)**
* **Buy/Sell signal generation**
* **Backtesting-ready outputs**
* **Data leakage-safe preprocessing**
* **Memory-efficient dataset handling**
* **GPU + Mixed Precision Training (AMP)**

---

## Project Architecture

```
Data → Feature Engineering → Scaling → Sequence Builder → Model → Prediction → Signal Engine
```

---

## Tech Stack

* **Python**
* **PyTorch**
* **NumPy / Pandas**
* **Scikit-learn**
* (Optional) Streamlit / FastAPI for deployment

---

## Model Details

* Sequence-based learning using **LSTM**
* Handles multi-stock time series data
* Supports:

  * Binary classification (Up/Down)
  * Future extension → Regression (returns)

---

## Features Used

* Returns & Log Returns
* Moving Averages (MA10, MA20)
* RSI (Relative Strength Index)
* Volume-based signals
* Price momentum indicators

---

## Training Details

* Loss: **Focal Loss** (handles class imbalance)
* Optimizer: **AdamW**
* Scheduler: **Cosine Annealing**
* Mixed Precision: Enabled

---

## Output

Model generates:

* Probability of price increase
* Trading signals (Buy / Sell)
* Confidence scores

---

## Key Optimizations

* No data leakage (proper train/val/test split)
* Vectorized feature engineering
* Memory-efficient dataset (no duplication)
* Optimized DataLoader (multi-worker + prefetch)
* Reduced training time significantly

---

## Future Improvements

* Replace LSTM → **Transformer / Temporal Fusion Transformer**
* Add **macroeconomic indicators**
* Use **Optuna for hyperparameter tuning**
* Build **backtesting engine**
* Deploy as **API + Dashboard**
* Add **Explainable AI (SHAP)**

---

## How to Run

```bash
# Clone repo
git clone https://github.com/akshat123-ai/ai-stock-prediction.git
cd ai-stock-prediction

# Install dependencies
pip install -r requirements.txt

# Run notebook / training script
```

---

## Use Cases

* Algorithmic trading research
* Quantitative finance projects
* Portfolio strategy development
* ML-based time series forecasting

---

## Disclaimer

This project is for **educational and research purposes only**.
It does **not guarantee financial profit** and should not be used as financial advice.

---

## Contributing

Pull requests are welcome. For major changes, please open an issue first.

---

## If you like this project

Give it a on GitHub — it helps!

---

## Contact

For queries or collaborations:

* GitHub: akshat123-ai
* Email: akshataws123@gmail.com
