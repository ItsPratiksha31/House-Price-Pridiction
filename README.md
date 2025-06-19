# House-Price-Pridiction

# 🏡 Boston House Price Prediction

A machine learning web application that predicts the median value of houses in Boston based on historical housing data. This project demonstrates the full ML workflow: data exploration, model training, evaluation, and deployment using Flask.

---

## 📌 Project Overview

This project uses the classic Boston Housing Dataset to predict home prices using 13 input features such as crime rate, number of rooms, tax rate, and more. A linear regression model is trained and deployed using a Flask web server with a simple HTML form interface for user input.

---

## 🎯 Objectives

- Perform Exploratory Data Analysis (EDA) on the Boston Housing dataset
- Build a regression model to predict house prices
- Evaluate the model using R² score and RMSE
- Deploy the model using Flask and create a user-friendly web interface

---

## 📊 Dataset Information

- **Source**: Scikit-learn’s Boston Housing Dataset  
- **Records**: 506  
- **Features**: 13 independent variables  
- **Target**: `MEDV` — Median value of homes in $1000s

### 📈 Key Features

| Feature | Description |
|--------|-------------|
| CRIM    | Crime rate per capita |
| ZN      | Residential land zoning proportion |
| INDUS   | Non-retail business acreage |
| CHAS    | Charles River dummy variable |
| NOX     | Nitric oxide concentration |
| RM      | Average number of rooms per dwelling |
| AGE     | Proportion of older units |
| DIS     | Distance to employment centers |
| RAD     | Highway accessibility index |
| TAX     | Property-tax rate |
| PTRATIO | Pupil-teacher ratio |
| B       | Black population proportion |
| LSTAT   | % of lower status population |

---

## 🧪 Technologies Used

| Category         | Tool/Library                     |
|------------------|----------------------------------|
| Language         | Python                           |
| ML Library       | scikit-learn                     |
| Data Analysis    | pandas, numpy                    |
| Visualization    | matplotlib, seaborn              |
| Web Framework    | Flask                            |
| Frontend         | HTML, CSS                        |
| Model Persistence| joblib                           |

---

## 📁 Project Structure

├── app.py # Flask application
├── house_price_prediction.pkl # Saved ML model
├── templates/
│ └── index.html # HTML form for input
├── static/
│ └── style.css # (Optional) Custom styles
├── requirements.txt # Python dependencies
└── README.md # Project documentation


## 🚀 How to Run the Project

### 🔧 Prerequisites

- Python 3.x
- pip (Python package manager)

### 📦 Install Dependencies

```bash
pip install -r requirements.txt

python app.py



