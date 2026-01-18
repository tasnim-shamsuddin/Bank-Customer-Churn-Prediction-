# Bank Customer Churn Prediction

## 📌 Project Overview

Customer churn is a critical problem in the banking sector. Retaining existing customers is often more cost-effective than acquiring new ones.
This project aims to **predict whether a bank customer will exit (churn) or not** using historical customer data and machine learning techniques.

The project follows a **structured end-to-end machine learning pipeline**, from data cleaning to model development.

---

## 🎯 Objective

To build a predictive model that classifies customers into:

* **Exited (1)** – Customer is likely to leave the bank
* **Not Exited (0)** – Customer is likely to stay

---

## 🗂 Dataset

The dataset contains customer demographic and banking information such as:

* Credit Score
* Geography
* Gender
* Age
* Balance
* Number of Products
* Active Member Status
* Estimated Salary
* Exit status (Target variable)

---

## ⚙️ Project Workflow

### 1️⃣ Data Cleaning

* Removed irrelevant columns (e.g., customer identifiers)
* Checked for missing values
* Ensured correct data types for numerical and categorical features

---

### 2️⃣ Encoding Categorical Features

* Encoded categorical variables such as:

  * Geography
  * Gender
* Converted categorical data into numerical format suitable for machine learning models

---

### 3️⃣ Feature & Target Separation

* **Features (X):** All independent variables
* **Target (y):** `Exited`

---

### 4️⃣ Saving the Preprocessed Data

* Saved the cleaned and encoded dataset using **pickle**
* This allows reuse of preprocessed data without repeating earlier steps

---

### 5️⃣ Train-Test Split

* Split the dataset into:

  * Training set
  * Testing set
* Ensured proper evaluation of model performance on unseen data

---

### 6️⃣ Neural Network Implementation (In Progress 🚧)

* A Neural Network model will be implemented using:

  * Input layer based on feature count
  * Hidden layers with activation functions
  * Output layer for binary classification
* Model performance will be evaluated using appropriate metrics

---

## 🧠 Models

* **Neural Network (Planned)**

  * Framework: TensorFlow / Keras or PyTorch
  * Loss Function: Binary Crossentropy
  * Optimizer: Adam

---

## 📊 Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* Confusion Matrix

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* NumPy
* Scikit-learn
* Pickle
* TensorFlow / Keras (for Neural Network)
* VS Code
* Git & GitHub

---

## 📁 Project Structure

```
bank-customer-churn-prediction/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   └── bank_customer_churn_analysis.ipynb
│
├── models/
│   └── preprocessed_data.pkl
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🚀 Future Enhancements

* Hyperparameter tuning for Neural Network
* Comparison with traditional ML models (Logistic Regression, Random Forest, XGBoost)
* Model deployment using Flask or FastAPI
* Dashboard visualization

---

## 👤 Author

**Tasnim Shamsuddin**
Aspiring Data Scientist
📍 Bahrain

---


