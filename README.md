# 🚗 Car Price Prediction
<img src="https://github.com/goldstring/car_price_predicion_using_machine_learning_regeression/blob/main/26234498_7197355.jpg?raw=true" />
A machine learning project to predict car prices based on various features such as year, brand, mileage, engine size, fuel type, transmission, and more.

## 📊 Project Overview

The goal of this project is to build a regression model that can accurately estimate the price of a car using features like:

- Year of manufacture
- Brand and model
- Mileage (km driven)
- Fuel type (Petrol, Diesel, etc.)
- Transmission (Manual/Automatic)
- Engine size
- Number of seats
- Owner type

## 🧠 Model Pipeline

**1. Data Collection**  
- Source: Kaggle Car Dataset

**2. Data Cleaning & EDA**  
- Handled missing values and outliers  
- Performed data visualization to understand feature distributions and correlations

**3. Feature Engineering**  
- Label Encoding for categorical variables  
- Feature scaling (StandardScaler)  
- Derived new features (e.g., car age)  

**4. Model Selection**  
Tested multiple regression algorithms:
- Linear Regression  
- Ridge/Lasso Regression  
- Random Forest Regressor  
- XGBoost Regressor  

**5. Evaluation Metrics**  
- Mean Absolute Error (MAE)  
- Root Mean Squared Error (RMSE)  
- R² Score  

**6. Model Deployment**  
- Final model saved to `models/car_price_model.pkl`  

## 📈 Results

✅ **Best Model**: Radom Forest Regressor  
✅ **R² Score on Test Set**: 0.95+  
✅ **MAE**: ~50,000  
✅ **RMSE**: ~80,000  

## 🚀 How to Run Locally

1. **Clone the repo**  
```bash
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction
