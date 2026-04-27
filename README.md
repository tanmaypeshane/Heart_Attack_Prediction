# ❤️ Heart Disease Prediction Web App

A Machine Learning-powered web application built using **Streamlit** that predicts the risk of heart disease based on user medical inputs.

---

## 🚀 Project Overview

This project uses a **Logistic Regression model** to analyze health parameters such as age, cholesterol, blood pressure, and more to predict whether a person is at **high risk or low risk of heart disease**.

The application provides a simple and interactive interface for users to input their details and instantly get predictions.

---

## 🧠 Features

* 📊 Real-time heart disease prediction
* 🧾 User-friendly input form
* ⚡ Fast and lightweight Streamlit app
* 📉 Uses trained ML model with preprocessing (scaling + encoding)
* 🎯 Displays clear result:

  * ✅ Low Risk
  * ⚠️ High Risk

---

## 🛠️ Tech Stack

* **Python**
* **Streamlit**
* **Pandas**
* **Scikit-learn**
* **Joblib**

---

## 📁 Project Structure

```
Heart_Disease_Project/
│
├── app.py                          # Main Streamlit application
├── logistic_Regression_heart.pkl   # Trained ML model
├── scaler.pkl                      # Scaler used during training
├── columns.pkl                     # Expected feature columns
├── requirements.txt                # Dependencies
└── README.md                       # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction
```

---

### 2️⃣ Create virtual environment (recommended)

```bash
python -m venv venv
source venv/bin/activate   # For Mac/Linux
venv\Scripts\activate      # For Windows
```

---

### 3️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4️⃣ Run the app

```bash
streamlit run app.py
```

---

## 📊 Input Features

The model uses the following parameters:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol Level
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* Oldpeak (ST Depression)
* ST Slope

---

## 🧪 Model Details

* **Algorithm:** Logistic Regression
* **Preprocessing:**

  * One-hot encoding for categorical variables
  * Feature scaling using StandardScaler
* **Output:**

  * `0` → Low Risk
  * `1` → High Risk

---

## ⚠️ Disclaimer

This application is for **educational purposes only** and should **not be used as a substitute for professional medical advice**.

---

## 📌 Future Improvements

* 📈 Add prediction probability score
* 🎨 Improve UI/UX design
* ☁️ Deploy on Streamlit Cloud
* 📊 Add data visualization dashboard
* 🤖 Try advanced models (Random Forest, XGBoost)

---

## 🙌 Author

**Tanmay**
Built with ❤️ using Python & Machine Learning

---

## 🌟 Show Your Support

If you like this project:

* ⭐ Star the repository
* 🍴 Fork it
* 🛠️ Contribute improvements

---
