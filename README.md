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


## Results
## TensorBoard Results

TensorBoard was used to monitor:
- Training loss
- Validation loss
- Accuracy



<img width="409" height="272" alt="image" src="https://github.com/user-attachments/assets/5d1c2875-29af-424e-a73c-882beee6ccfc" />




<img width="412" height="363" alt="image" src="https://github.com/user-attachments/assets/bf4ad3ba-4dbd-4405-824a-b354a47fd59b" />

<img width="409" height="377" alt="image" src="https://github.com/user-attachments/assets/a9269212-e98e-4e76-82a4-10c28e4f7c39" />

<img width="416" height="381" alt="image" src="https://github.com/user-attachments/assets/55969fe6-0ef6-4402-a606-470483d0b638" />
<img width="419" height="387" alt="image" src="https://github.com/user-attachments/assets/b005f70d-78e0-4ff6-9211-171d24dee65d" />
The model shows stable convergence with decreasing loss and improving validation accuracy, 
indicating good generalization without overfitting.

---

## 🚀 Future Enhancements

* Hyperparameter tuning for Neural Network
* Comparison with traditional ML models (Logistic Regression, Random Forest, XGBoost)
* Model deployment using Flask or FastAPI


---

## 👤 Author

**Tasnim Shamsuddin**
Aspiring Data Scientist
📍 Bahrain

---


