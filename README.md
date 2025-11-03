# 🌾 Precision Agriculture and Yield Prediction

## 📘 Project Overview
This project focuses on using **machine learning techniques** to enhance **precision agriculture** — enabling farmers to make data-driven decisions and predict crop yields accurately.  
By analyzing various agricultural parameters such as soil health, weather conditions, rainfall, humidity, and temperature, the model helps optimize resource usage and improve overall productivity.

---

## 🎯 Objectives
- To analyze agricultural datasets and identify factors affecting crop yield.  
- To build a **machine learning model** that predicts crop yield based on environmental and soil features.  
- To support **smart farming practices** using data-driven insights.

---
## 📊 Dataset Description

The dataset used in this project contains agricultural data collected from various regions to predict crop yield.  
Each record represents a unique combination of environmental, soil, and cultivation parameters.

| Feature | Description | Data Type | Example |
|----------|--------------|------------|----------|
| **Region** | Geographic area where crops are cultivated | Categorical | South, North, East |
| **Soil_Type** | Type of soil in the region | Categorical | Loamy, Sandy, Clay |
| **Crop** | Type of crop being cultivated | Categorical | Rice, Wheat, Maize |
| **Rainfall_mm** | Total rainfall during the cultivation period (in millimeters) | Numerical | 425 |
| **Temperature_Celsius** | Average temperature during the growth period (°C) | Numerical | 28 |
| **Fertilizer_Used** | Amount of fertilizer applied (kg/hectare) | Numerical | 120 |
| **Irrigation_Used** | Type of irrigation used | Categorical | Drip, Sprinkler, Canal |
| **Weather_Condition** | General weather condition during crop growth | Categorical | Sunny, Cloudy, Rainy |
| **Days_to_Harvest** | Number of days required for crop maturity | Numerical | 120 |
| **Yield_tons_per_hectare** | Final yield produced per hectare (Target variable) | Numerical | 3.5 |

### 🔍 Insights:
- The dataset combines **environmental** and **management factors** affecting crop production.  
- Features like **Rainfall**, **Temperature**, and **Fertilizer Used** show a strong correlation with yield.  
- The target variable (**Yield_tons_per_hectare**) helps in evaluating model accuracy for prediction.

---

### 💾 File Format
- File Name: `agriculture_data.csv`  
- Format: CSV (Comma Separated Values)  
- Rows: *n* (number of observations)  
- Columns: 10  

---

### 📈 Example Row

| Region | Soil_Type | Crop | Rainfall_mm | Temperature_Celsius | Fertilizer_Used | Irrigation_Used | Weather_Condition | Days_to_Harvest | Yield_tons_per_hectare |
|---------|------------|------|--------------|----------------------|------------------|------------------|-------------------|------------------|-------------------------|
| South | Loamy | Rice | 420 | 29 | 110 | Drip | Sunny | 120 | 3.8 |

---
## ⚙️ Tools & Technologies
- **Programming Language:** Python  
- **Notebook Environment:** Jupyter Notebook  
- **Libraries Used:**  
  - `pandas` for data manipulation  
  - `numpy` for numerical analysis  
  - `matplotlib` & `seaborn` for data visualization  
  - `scikit-learn` for machine learning algorithms  
  - `joblib` for model saving/loading  

---

## 🧠 Methodology
1. **Data Collection:** Import and explore the dataset.  
2. **Data Preprocessing:** Handle missing values, normalization, and encoding.  
3. **Exploratory Data Analysis (EDA):** Visualize trends and correlations.  
4. **Model Building:** Train multiple ML models (e.g., Linear Regression, Random Forest, XGBoost).  
5. **Model Evaluation:** Compare performance using metrics such as R² score, MAE, and RMSE.  
6. **Prediction:** Use the trained model to predict crop yield for new input data.  

---

## 📊 Results
- Achieved high accuracy in yield prediction using Random Forest Regressor.  
- Identified key influencing factors for better crop management.  
- Improved yield estimation and resource allocation insights.

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Precision-Agriculture-and-Yield-Prediction.git
