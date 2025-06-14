# 🚦 Traffic Volume Forecasting using Deep Learning

This project aims to forecast traffic volume using advanced deep learning models such as Vanilla Transformer, Autoformer, and Informer. It uses time-series data and sequence modeling to predict future traffic patterns for better urban planning and congestion management.

---

## 📊 Models Implemented

- **Vanilla Transformer**: Baseline Transformer model for sequence prediction.
- **Autoformer**: Designed for long-term time series forecasting using series decomposition.
- **Informer**: Efficient Transformer variant for long sequences with sparse attention.

---

## 🧪 Evaluation Metrics

| Model              | MAE     | RMSE     |
|-------------------|---------|----------|
| Vanilla Transformer | 42,246.37 | 53,170.21 |
| Autoformer        | 0.59    | 0.57     |
| Informer          | 2.81    | 8.48     |

> Note: Autoformer and Informer were evaluated on scaled data (normalized), while Vanilla used raw values.

---

## 📂 Project Structure

- `Traffic_Forecasting_Colab.ipynb`: Main code implementation and evaluation
- `data/`: (optional) Processed data or sample input
- `plots/`: Visualization results (bar charts, predictions vs actual)

---

## 🚀 How to Run

1. Clone this repo
2. Open the notebook in Google Colab or Jupyter
3. Install required libraries (PyTorch, sklearn, matplotlib)
4. Run all cells step-by-step to train and evaluate models

---

## 📈 Key Skills Used

- Time Series Forecasting
- Deep Learning (PyTorch)
- Transformers (Vanilla, Autoformer, Informer)
- Data Preprocessing & Scaling
- Model Evaluation (MAE, RMSE)
- Visualization (Matplotlib, Bar Chart)

---

## 🔗 Demo / Presentation

[Optional: Add Colab link, YouTube presentation, or project PDF/report here]

---

## 👩‍💻 Author

**Shakshi Pal**  
Data Science Enthusiast | Python & ML | GitHub: [@Shakshi123pal](https://github.com/Shakshi123pal)
