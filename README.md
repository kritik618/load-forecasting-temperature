## Load Forecasting Using Temperature Data

## 🌡️ Overview

This project focuses on forecasting electrical load based on historical temperature data. A vanilla benchmark model is implemented using linear regression to establish a baseline for future model comparisons.

The dataset contains hourly data points and is divided into training and testing windows for model evaluation.

---

## 🧪 Methods Used

- Time-series structured train-test split
- Multiple regression with `statsmodels`
- Feature: `Trend` (to account for temporal progression)
- Evaluation on vanilla benchmark to compare with future models

---

## 📊 Dataset Description

> ⚠️ Note: The dataset is not included due to size and privacy.

The dataset was imported from an Excel file and contains the following features:

- `Date`: Timestamp (hourly)
- `Temperature`: External temperature
- `Load`: Actual electricity consumption
- `Trend`: Created index feature to capture time progression

---

## 📂 File Structure
notebooks/ └── homework_3_benchmark.ipynb # Contains full workflow: data load, train-test split, modeling, and evaluation


---

## 📈 Output

- Visual comparison of predicted vs actual load
- Error metrics (e.g., RMSE or MAE, if added later)
- Plots generated using `matplotlib`

---

## 📦 Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- statsmodels

