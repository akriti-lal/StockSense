# StockSense – Walmart Sales Prediction

## 📌 Project Overview

StockSense is a Machine Learning project for predicting weekly sales using historical Walmart sales data.

The project analyzes factors such as store information, holidays, temperature, fuel price, CPI, unemployment, and time-based features to predict weekly sales.

## 🎯 Objective

The main objective of this project is to build a machine learning model that can predict future weekly sales and support better inventory and demand planning.

## 📊 Dataset

The project uses the Walmart Sales dataset.

Important features include:

- Store
- Date
- Weekly Sales
- Holiday Flag
- Temperature
- Fuel Price
- CPI
- Unemployment

Additional features were created from the date:

- Year
- Month
- Week
- Time Index

## 🤖 Machine Learning Models

The following regression algorithms were tested:

1. Linear Regression
2. Decision Tree Regressor
3. Random Forest Regressor
4. Gradient Boosting Regressor

## 📈 Model Results

| Model | MAE | RMSE | R² Score |
|---|---:|---:|---:|
| Linear Regression | 434402.08 | 518013.41 | 0.1392 |
| Decision Tree | 74118.79 | 150847.03 | 0.9270 |
| Random Forest | 61160.11 | 122444.87 | 0.9519 |
| Gradient Boosting | 129422.39 | 170594.47 | 0.9066 |

On the current train-test split, the Random Forest model achieved the highest R² score and the lowest MAE and RMSE among the tested models.

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook
- VS Code

## 📁 Project Structure

```text
StockSense/
│
├── .venv/
├── Walmart.csv
├── sales_prediction.ipynb
├── walmart_random_forest_model.pkl
├── requirements.txt
└── README.md