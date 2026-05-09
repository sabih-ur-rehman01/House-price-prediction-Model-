# House-price-prediction-Model-
This project is an end-to-end Machine Learning + Data Visualization web application that predicts California house prices using the California Housing dataset. It includes feature engineering, outlier handling, model training using XGBoost Regressor, and an interactive Dash dashboard for live predictions and visual insights.

An advanced Machine Learning dashboard for predicting house prices using **XGBoost**, **Dash**, and **Plotly**.

This project performs:

- 📊 Data Analysis
- 🧹 Data Cleaning
- ⚙️ Feature Engineering
- 🤖 Machine Learning Prediction
- 📈 Interactive Visualizations
- 🏠 Live House Price Prediction

---

# Features

## Data Visualization
- House price distribution
- Correlation heatmap
- Feature importance chart
- Dataset statistics dashboard

## Machine Learning
- XGBoost Regressor model
- High accuracy regression prediction
- Real-time prediction system

## Feature Engineering
Custom engineered features including:
- Rooms per household
- Bedrooms per room
- Population per household
- Income per room
- Bedroom ratio
- Room population ratio

## Data Preprocessing
- Missing value handling
- Outlier detection using IQR
- Feature scaling preparation

## Live Prediction Dashboard
Interactive sliders for:
- Median Income
- House Age
- Total Rooms
- Population

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Dash
- Scikit-learn
- XGBoost

---

# Installation

## Install Dependencies

```bash
pip install -r requirements.txt
```

---

## Run Application

```bash
python app.py
```

---

# Machine Learning Model

The project uses:

## XGBoost Regressor

```python
XGBRegressor(
    n_estimators=1000,
    learning_rate=0.02,
    max_depth=7,
    subsample=0.9,
    colsample_bytree=0.9,
    random_state=42
)
```

---

# Dashboard Components

- 📉 Histogram of house prices
- 🔥 Correlation heatmap
- 📌 Feature importance graph
- 📍 Real-time prediction panel

---

# Workflow

1. Load housing dataset
2. Handle missing values
3. Create engineered features
4. Remove outliers
5. Train XGBoost model
6. Evaluate model performance
7. Visualize data
8. Predict house prices live

---
