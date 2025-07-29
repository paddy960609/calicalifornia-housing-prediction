# California Housing Price Prediction 🏡

This project uses the California Housing dataset to predict median house values using an XGBoost regressor.

## 📦 Features
- Combines training and test data from Kaggle
- Preprocessing with `StandardScaler`
- Trains an XGBoost Regressor
- Evaluates model performance using RMSE and R²
- Saves model and scaler for future use

## 🛠 Requirements
See `requirements.txt` for full dependencies.

## 🚀 How to Run

```bash
pip install -r requirements.txt
python train_model.py
```

## 📊 Output
- Trained model score
- RMSE and R² metrics
- Histogram of housing data
- Saved model and scaler under `/models`

## 📁 Directory Structure
```
.
├── train_model.py
├── requirements.txt
├── README.md
├── models/
└── data/
```

## 🔗 Dataset
Downloaded from Kaggle: https://www.kaggle.com/datasets/camnugent/california-housing-prices
