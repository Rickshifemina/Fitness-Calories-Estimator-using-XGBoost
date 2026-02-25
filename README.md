# Fitness-Calories-Estimator-using-XGBoost


## 📌 Project Overview

This project is an **end-to-end Machine Learning application** that predicts the number of calories burned during exercise based on user body metrics and exercise parameters.

The project includes:

* Data Analysis & Visualization
* Machine Learning Model Training using XGBoost
* Model Deployment using Streamlit Web App

---

## 🎯 Problem Statement

Predict calories burned using:

* Gender
* Age
* Height
* Weight
* Exercise Duration
* Heart Rate
* Body Temperature

---

## 📊 Dataset Information

Dataset contains **15,000+ records** with:

### Features:

* User_ID
* Gender
* Age
* Height
* Weight
* Duration
* Heart_Rate
* Body_Temp

### Target:

* Calories

---

## ⚙️ Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib & Seaborn
* Scikit-Learn
* XGBoost
* Streamlit
* Pickle

---

## 📈 Machine Learning Workflow

### 1. Data Preprocessing

* Merged exercise and calories dataset
* Converted categorical data to numeric
* Checked missing values

### 2. Exploratory Data Analysis

* Distribution plots
* Correlation heatmap
* Feature relationship analysis

### 3. Model Training

Algorithm Used:

**XGBoost Regressor**

* Train-Test Split: 80:20
* Evaluation Metric: Mean Absolute Error

### 4. Model Saving

Model saved using Pickle:

```bash
calories_model.pkl
```

---

## 🌐 Streamlit Web Application

Interactive web app where users enter:

* Age
* Gender
* Weight
* Height
* Heart Rate
* Duration
* Body Temperature

And get:

✅ Real-time calories prediction

---

## 🚀 How to Run Project

### Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/calories-burn-predictor.git
```

---

### Step 2: Install Requirements

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost streamlit
```

---

### Step 3: Run Model Notebook

```bash
model1.ipynb
```

---

### Step 4: Run Streamlit App

```bash
streamlit run app.py
```

---

## 📁 Project Structure

```
├── model1.ipynb
├── app.py
├── calories.csv
├── exercise.csv
├── calories_model.pkl
└── README.md
```

---

## 📊 Model Performance

* Algorithm: XGBoost Regressor
* Evaluation Metric: Mean Absolute Error
* High accuracy prediction

---

## 💡 Key Features

✔ End-to-End ML Project
✔ Real-world dataset
✔ Web App Deployment
✔ Interactive UI
✔ Production-Ready Model

---

## 🎯 Future Improvements

* Deploy on cloud (AWS / Render)
* Add user authentication
* Improve UI
* Use Deep Learning

---

## 👤 Author

Rickshi

LinkedIn: https://linkedin.com/in/rickshi-femina

Email: [rickshi2526@gmail.com](mailto:rickshi2526@gmail.com)

---

