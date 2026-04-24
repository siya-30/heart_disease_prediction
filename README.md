# 💓 Heart Disease Prediction Web App

A machine learning-based web application that predicts the risk of heart disease using clinical parameters. The system provides real-time predictions through a clean and premium user interface.

---

## 🚀 Features

* 🔍 Predicts heart disease risk using a trained ML model
* 🎯 Premium UI with dropdown-based inputs (no manual coding needed by user)
* ⚡ Real-time prediction using Flask backend
* 📊 Handles multiple clinical parameters (BP, cholesterol, heart rate, etc.)
* 💡 Clean, responsive, and user-friendly design

---

## 🧠 Tech Stack

* **Frontend:** HTML, CSS (Glassmorphism UI)
* **Backend:** Flask (Python)
* **Machine Learning:** Random Forest Classifier (Scikit-learn)
* **Dataset:** Heart Disease Dataset

---

## 📸 Screenshots

### 🖥️ Main Interface
<img src="https://raw.githubusercontent.com/siya-30/heart_disease_prediction/main/images/ui.jpeg" width="800"/>

### 📊 Prediction Result
<img src="https://raw.githubusercontent.com/siya-30/heart_disease_prediction/main/images/result.jpeg" width="800"/>
---

## 📂 Project Structure

```
heart-disease-predictor/
│
├── app.py
├── model.pkl
├── heart.csv
├── model.ipynb
├── templates/
│   └── index.html
└── images/
    ├── ui.png
    └── result.png
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the repository

```
git clone https://github.com/your-username/heart-disease-predictor.git
cd heart-disease-predictor
```

### 2️⃣ Install dependencies

```
pip install flask pandas scikit-learn
```

### 3️⃣ Run the application

```
python app.py
```

### 4️⃣ Open in browser

```
http://127.0.0.1:5000/
```

---

## 📈 Model Details

* Algorithm: **Random Forest Classifier**
* Train/Test Split: 80/20
* Target Variable: `target`

### Input Features:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Rest ECG
* Maximum Heart Rate
* Exercise Induced Angina
* Oldpeak
* Slope
* Number of Major Vessels
* Thal

---

## 💡 Future Improvements

* 📊 Add prediction probability (% risk)
* 🎯 Add smarter validation and suggestions
* 🌐 Deploy on AWS / Render
* 📉 Add analytics dashboard

---

## 💼 Resume Highlight

Developed a machine learning-based heart disease prediction web application using Flask and Random Forest, featuring an interactive UI for real-time clinical risk assessment.

---

## 👩‍💻 Author

**Siya Dumale**

---
