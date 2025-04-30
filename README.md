# AQI Prediction and Model Comparison

This project uses machine learning models to predict Air Quality Index (AQI) using publicly available data and compares their performance using key metrics.

## 📊 Dataset

- **Source**: [Kaggle AQI Dataset](https://www.kaggle.com/datasets/rohanrao/air-quality-data-in-india?resource=download)
- Features include PM2.5, PM10, NO2, SO2, CO, O3, etc.
- Target: AQI value

## 🔧 Project Highlights

- Applied models: **SVM, KNN, Random Forest, XGBoost, ElasticNet**
- Metrics used: **RMSE, R², MAE**
- Used **K-Fold Cross Validation** for robust evaluation
- Data preprocessing using **Pandas** and **scikit-learn**
- Visualized trends and comparisons with **Matplotlib** and **Seaborn**

## 📂 Structure

- `data/`: Raw dataset
- `notebooks/`: Main Jupyter notebook with full EDA and model training
- `src/`: Preprocessing and model utilities
- `README.md`: This file
- `requirements.txt`: List of required packages

## 📈 Results Summary

| Model          | RMSE   | R²     | MAE    |
|----------------|--------|--------|--------|
| Random Forest  | 18.25  | 0.89   | 12.76  |
| XGBoost        | 17.90  | 0.90   | 12.35  |
| SVM            | 22.45  | 0.81   | 16.10  |
| KNN            | 24.70  | 0.78   | 17.80  |
| ElasticNet     | 26.80  | 0.76   | 19.30  |

> Results will vary based on exact dataset preprocessing and splits.

## 🛠️ Installation

```bash
git clone https://github.com/yourusername/aqi-prediction-comparison.git
cd aqi-prediction-comparison
pip install -r requirements.txt
