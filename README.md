# 🦠 COVID-19 Time Series Forecasting & Model Comparison

This project explores various time series forecasting techniques for predicting COVID-19 deaths using real-world global datasets. We apply and compare multiple models including SARIMAX, Prophet, XGBoost, and a Feedforward Neural Network to identify which method yields the most accurate and actionable forecasts.

---

## 📈 Business Context

Forecasting COVID-19 deaths can support critical decision-making in public health, such as hospital capacity planning, lockdown strategies, and vaccine distribution. This project simulates how data professionals can use time series analytics to guide real-world crisis management.

---

## 🛠 Project Tasks

- **Task 1**: Preprocess the data using `pandas` to prepare for modeling and visualize key trends using `matplotlib`.
- **Task 2**: Build a **SARIMAX** model, optimize hyperparameters, forecast COVID-19 deaths, and visualize results.
- **Task 3**: Build a **Prophet** model to forecast COVID-19 deaths and visualize predictions.
- **Task 4**: Create a feature extraction function for training **XGBoost** and a **Feedforward Neural Network**.
- **Task 5**: Split the dataset into training/test sets and perform **data normalization**.
- **Task 6**: Train **XGBoost** and **Neural Network** models, and **compare predictions** from all models.

---

## 🧰 Tools & Technologies

- **Languages**: Python (Pandas, NumPy)
- **Visualization**: Matplotlib, Seaborn
- **Modeling**: SARIMAX (`statsmodels`), Prophet (`fbprophet`), XGBoost, Neural Network (`Keras/TensorFlow`)

---

## 🔬 Methodology

- Aggregated daily COVID-19 deaths globally
- Transformed time series data into supervised learning format for ML models
- Modeled trends and seasonality using SARIMAX and Prophet
- Engineered features for lag-based models (XGBoost and FFNN)
- Evaluated performance through visualizations and metrics (e.g., RMSE, MAE)

---

## 🧠 Key Takeaways

- **SARIMAX** performed well with stable historical trends  
- **Prophet** handled irregularities and missing values effectively  
- **XGBoost** captured non-linear patterns but required more tuning  
- **Feedforward Neural Network** showed potential but was sensitive to data volume

---

