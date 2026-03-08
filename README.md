# Customer Analytics ML Apps (ANN Classification & Regression)

![Python](https://img.shields.io/badge/Python-3.11-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Keras-orange)
![Streamlit](https://img.shields.io/badge/Streamlit-Web%20App-red)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-ANN-green)

This repository contains **two deployed Machine Learning web applications** built using **Artificial Neural Networks (ANN)** and deployed with **Streamlit**.

The applications demonstrate how neural networks can be used for both **classification and regression problems** in real-world business scenarios.

---

# Projects in this Repository

## 1️⃣ Customer Churn Prediction (Classification)

This application predicts whether a **bank customer is likely to leave the bank (churn)**.

The model is trained using an **Artificial Neural Network (ANN)** on customer banking data.

### Example Inputs

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Active Member
- Estimated Salary

### Output

```
Customer is likely to churn
```

or

```
Customer will stay with the bank
```

### Model Type
Artificial Neural Network (ANN)

### Files Used

```
app.py
model.h5
label_encoder_gender.pkl
onehot_encoder_geo.pkl
scaler.pkl
Churn_Modelling.csv
```

---

# 2️⃣ Salary Prediction (Regression)

This application predicts **customer salary values using a neural network regression model**.

### Model Type
ANN Regression Model

### Output

Predicted numeric salary value.

Example:

```
Predicted Salary: $72,450
```

### Files Used

```
regressionapp.py
regression_model.h5
scaler.pkl
```

---

# Technologies Used

| Technology | Purpose |
|------------|---------|
Python | Programming language |
TensorFlow / Keras | Neural network modeling |
Streamlit | Interactive web app |
Scikit-learn | Data preprocessing |
Pandas | Data manipulation |
NumPy | Numerical computing |

---

# Project Structure

```
│
├── app.py                      # Churn prediction Streamlit app
├── regressionapp.py            # Regression prediction Streamlit app
│
├── model.h5                    # ANN classification model
├── regression_model.h5         # ANN regression model
│
├── label_encoder_gender.pkl
├── onehot_encoder_geo.pkl
├── scaler.pkl
│
├── Churn_Modelling.csv
│
├── experiments.ipynb           # Model training experiments
├── prediction.ipynb            # Prediction testing
│
├── requirements.txt
├── runtime.txt
└── README.md
```

---

# How to Run the Applications

## Clone the repository

```
git clone https://github.com/YOUR_USERNAME/YOUR_REPOSITORY.git
cd YOUR_REPOSITORY
```

---

## Create virtual environment

```
python -m venv venv
source venv/bin/activate
```

---

## Install dependencies

```
pip install -r requirements.txt
```

---

# Run Churn Prediction App

```
streamlit run app.py
```

---

# Run Regression Prediction App

```
streamlit run regressionapp.py
```

---

# Dataset

Dataset used: **Churn Modelling Dataset**

Features include:

- Credit Score
- Geography
- Gender
- Age
- Tenure
- Balance
- Number of Products
- Has Credit Card
- Active Member
- Estimated Salary

---

# Future Improvements

- Improve feature engineering
- Add model performance visualization
- Add explainable AI (SHAP)
- Deploy using Docker
- Improve UI/UX of Streamlit applications

---


# License

This project is created for **educational and portfolio purposes**.
