# TASK - 3 Car Price Prediction using Machine Learning

## 📘 Objective
The objective of this project is to develop a machine learning model that accurately predicts the price of a car based on various attributes such as brand, model year, mileage, fuel type, transmission, and other relevant factors.

---

## 🧩 Steps Performed

### 1. **Data Loading and Preprocessing**
- Imported required libraries such as `pandas`, `numpy`, and `sklearn`.
- Loaded the dataset and performed an initial exploration.
- Checked for null values, duplicates, and irrelevant columns.
- Cleaned and prepared the data for training.

### 2. **Feature Engineering**
- Converted categorical variables (like brand, fuel type, and transmission) into numerical form using **Label Encoding** or **One-Hot Encoding**.
- Scaled numerical features using **StandardScaler** for model efficiency.
- Handled outliers and normalized skewed data.

### 3. **Model Building**
- Implemented an **XGBoost Regressor (XGBRegressor)** for robust price prediction.
- Created a **Pipeline** for cleaner and modular model construction.
- Split the data into **training and testing sets** using `train_test_split`.

### 4. **Model Evaluation**
- Evaluated performance using metrics such as:
  - **R² Score**
  - **Mean Squared Error (MSE)**
  - **Root Mean Squared Error (RMSE)**
- Compared predicted prices with actual prices to assess accuracy.

### 5. **Model Saving**
- Serialized (saved) the trained model using **Pickle** for future use.
- Enabled model reusability without retraining.

---

## ⚙️ Tools & Libraries Used
| Category | Tools/Libraries |
|-----------|----------------|
| Data Handling | `pandas`, `numpy` |
| Machine Learning | `xgboost`, `scikit-learn` |
| Model Evaluation | `r2_score`, `mean_squared_error`, `math` |
| Model Deployment | `pickle` |

---

## 🏁 Outcome
- Successfully built a **car price prediction model** capable of estimating market prices with high accuracy.
- Achieved a strong **R² score**, indicating excellent predictive performance.
- The project demonstrates end-to-end ML workflow — from data preprocessing to model deployment.

---


