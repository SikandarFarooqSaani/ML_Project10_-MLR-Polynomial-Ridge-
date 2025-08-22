# 🏡 Real Estate Price Prediction – Polynomial Regression Practice  

This is a small **machine learning practice project** where I experimented with regression models to predict real estate prices.  
The dataset is from Kaggle, and I tested **Linear Regression, Polynomial Regression, KNN, and Ridge Regression**.  

---

## 📊 Dataset  
- Source: [Real Estate Price Prediction Dataset](https://www.kaggle.com/datasets/quantbruce/real-estate-price-prediction)  
- Dropped the **serial number** column  
- No missing values  
- No duplicates  

---

## ⚙️ Steps  

1. **Libraries used**  
   - `numpy`, `pandas`, `matplotlib`  
   - `sklearn` → `model_selection`, `linear_model`, `PolynomialFeatures`, `StandardScaler`, `SGDRegressor`, `Ridge`, `KNeighborsRegressor`  
   - `pipeline`, `r2_score`  
   - `os`, `kagglehub`  

2. **Preprocessing**  
   - Created `X` (features) and `y` (target)  
   - Train-test split: **80:20 ratio**, `random_state=2`  

3. **Models and Results**  
   - **Linear Regression** → R² = **0.51**  
   - **Polynomial Regression** (degree 2, tried with/without bias, different degrees) → Best R² = **0.56**  
   - **KNN Regression** (k=9, weights=distance, p=1 Manhattan) → R² = **0.61**  
   - **Ridge Regression** → R² = **0.51**  

---

## 🚀 Conclusion  
- Polynomial Regression improved results slightly over Linear Regression.  
- KNN gave the best score (**0.61 R²**) in this practice.  
- Ridge did not improve results.  
- This is just a **practice project**. I’ll try more algorithms later to get better performance.  

---
