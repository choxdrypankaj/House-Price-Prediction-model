# 🏠 HOUSE PRIZE PREDICTIN -MODEL

A Machine Learning project that predicts the median value of owner-occupied homes in Boston suburbs using regression algorithms.

---

## 📌 Project Overview

This project implements an end-to-end machine learning pipeline to estimate house prices based on various socio-economic, environmental, and housing features.

The dataset used is the **Boston Housing Dataset** from the UCI Machine Learning Repository, containing 506 records with 13 input features.

This project demonstrates the full data science workflow including:

- Data preprocessing  
- Exploratory Data Analysis (EDA)  
- Feature scaling  
- Model training  
- Model evaluation  
- Price prediction  

---

## 🎯 Problem Statement

House prices depend on multiple factors such as crime rate, number of rooms, pollution level, and accessibility to highways. Manual estimation is often inaccurate and subjective.

The goal of this project is to build a **data-driven regression model** that can accurately predict housing prices.

---

## 📊 Dataset Information

- 📍 Source: UCI Machine Learning Repository  
- 🔢 Total samples: 506  
- 📥 Input features: 13  
- 🎯 Target variable: `price`  
- 🧠 Problem type: Regression  
- 📅 Data collected: 1978  

---

## 🧾 Features Description

| Feature | Description |
|--------|-------------|
| crim | Per capita crime rate by town |
| zn | Residential land zoning proportion |
| indus | Non-retail business acres proportion |
| chas | Charles River dummy variable (0/1) |
| nox | Nitric oxide concentration |
| rm | Average number of rooms |
| age | Proportion of old houses |
| dis | Distance to employment centers |
| rad | Highway accessibility index |
| tax | Property tax rate |
| ptratio | Pupil-teacher ratio |
| b | Demographic index (legacy variable) |
| lstat | % lower status population |

**Target:** `price` — Median house value (in $1000s)

---

## 🔍 Exploratory Data Analysis

Key analysis performed:

- Dataset inspection  
- Statistical summary  
- Correlation heatmap  
- Distribution plots  
- Outlier detection  
- Feature vs price relationships  

### 📌 Important Insights

- `rm` has strong positive correlation with price  
- `lstat` has strong negative correlation with price  
- Some multicollinearity exists  
- Data contains skewed features  

---

## 🧹 Data Preprocessing

The following preprocessing steps were applied:

- Checked missing values  
- Feature scaling using StandardScaler  
- Train-test split (80-20)  
- Feature-target separation  

---

## 🤖 Models Used

- Linear Regression (baseline)  
- Random Forest Regressor *(if used)*  
- Decision Tree Regressor *(if used)*  
- Gradient Boosting *(optional)*  

---

## 📈 Evaluation Metrics

Model performance is evaluated using:

- Mean Absolute Error (MAE)  
- Mean Squared Error (MSE)  
- Root Mean Squared Error (RMSE)  
- R² Score ⭐  

---

## 🏆 Results

The best model was selected based on highest R² score and lowest error metrics.

*(👉 You can add your actual scores here later)*

---

## 📁 Project Structure


House-Price-Prediction-model/
│
├── data/
├── notebooks/
├── src/
├── models/
├── requirements.txt
├── README.md
└── app.py (optional)


---

## 🚀 How to Run

### 1️⃣ Clone the repository

```bash
git clone https://github.com/choxdrypankaj/House-Price-Prediction-model.git
cd House-Price-Prediction-model
2️⃣ Install dependencies
pip install -r requirements.txt
3️⃣ Run the model
python train.py
python predict.py
⚠️ Important Note

The Boston Housing dataset has been deprecated in newer versions of sklearn due to ethical concerns regarding one feature. However, it is still widely used for educational and practice purposes.

🔮 Future Improvements

Hyperparameter tuning

Cross-validation

Feature importance visualization

Streamlit web app

Model deployment

Larger real-world dataset

🧠 Skills Demonstrated

Data Cleaning

Exploratory Data Analysis

Feature Engineering

Regression Modeling

Model Evaluation

Machine Learning Pipeline

Python & scikit-learn

👨‍💻 Author

Pankaj
🎓 Data Science Student
🔗 GitHub: https://github.com/choxdrypankaj
