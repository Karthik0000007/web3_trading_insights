# 🚀 Trader Classification using XGBoost

This project builds a machine learning pipeline to classify traders as either **High Risk** or **Low Risk** based on their trading behaviors using an XGBoost classifier.

## 📁 Project Structure
```bash
ds_M.SairamKarthik/
├── csv_files/
├── outputs/
├── notebook_1.ipynb
├── notebook_2.ipynb
├── requirements.txt
└── README.md
```

---

## 📌 Objective

To build an end-to-end machine learning model using **XGBoost** that:
- Cleans and processes the input trade data
- Extracts meaningful features from raw timestamps
- Trains a robust binary classifier
- Outputs predictions for the provided test data

---

## 📊 Features Used

- **price**, **volume**, **pnl**, **trade_count**
- **Time-based features**: hour, minute, second, etc.
- **Aggregated statistics**: mean, standard deviation, etc.

---

## ⚙️ ML Pipeline Overview

1. **Data Preprocessing**
   - Loaded raw CSV files from `/csv_files`
   - Extracted time-based features
   - Filtered and aggregated necessary stats

2. **Model Training**
   - Trained XGBoost classifier
   - Evaluated using classification report, confusion matrix

3. **Prediction**
   - Inference on test set
   - Saved outputs to `/outputs/predictions.csv`

---

## 📈 Results Summary

- XGBoost achieved strong performance on training data.
- Data analysis showed **very low or negative correlation** between raw features, making engineered features essential.

---

## 🧪 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

