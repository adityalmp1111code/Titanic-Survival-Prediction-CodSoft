# 🚢 Titanic Survival Prediction

## 📖 Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning. The model is built from scratch using NumPy and Logistic Regression without relying on pre-built machine learning algorithms.

The prediction is based on passenger information such as passenger class, gender, age, and fare.

---

## 🎯 Project Objective

The goal of this project is to analyze Titanic passenger data and build a classification model that can predict survival outcomes based on passenger characteristics.

---

## 📂 Dataset Features

The dataset contains the following features:

- Passenger Class (Pclass)
- Gender (Sex)
- Age
- Fare
- Embarked
- Survival Status (Target Variable)

### Target Variable

- 0 = Did Not Survive
- 1 = Survived

---

## 🛠 Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Loading
- Load Titanic dataset using Pandas.

### 2. Data Cleaning
- Handle missing values.
- Fill missing Age values using median.
- Fill missing Embarked values using mode.

### 3. Data Preprocessing
- Convert categorical features into numerical values.
- Normalize feature values.

### 4. Exploratory Data Analysis
- Survival count visualization.
- Survival by gender.
- Survival by passenger class.

### 5. Model Building
- Implement Logistic Regression from scratch.
- Define Sigmoid Function.
- Initialize weights and bias.
- Train using Gradient Descent.

### 6. Prediction
- Predict survival probabilities.
- Convert probabilities into class labels.

### 7. Evaluation
- Calculate model accuracy.
- Test predictions on new passenger data.

---

## 📊 Visualizations

The project includes:

- Survival Count Chart
- Survival by Gender
- Survival by Passenger Class

These visualizations help understand the factors affecting passenger survival.

---

## 🤖 Machine Learning Algorithm

### Logistic Regression (From Scratch)

The model uses:

- Sigmoid Activation Function
- Gradient Descent Optimization
- Binary Classification

No pre-built Logistic Regression model from Scikit-Learn was used.

---

## 📁 Project Structure

Titanic-Survival-Prediction/

├── TITANIC SURVIVAL PREDICTION.ipynb

├── Titanic-Dataset.csv

├── README.md

└── requirements.txt

---

## 📦 Requirements

```txt
pandas
numpy
matplotlib
jupyter
```

---

## 🚀 Future Improvements

- Train/Test Split implementation
- Accuracy, Precision, Recall, F1 Score evaluation
- Confusion Matrix visualization
- Comparison with Scikit-Learn models
- Streamlit Web Application Deployment

---

## 🏁 Conclusion

This project demonstrates how Logistic Regression can be implemented from scratch using NumPy to solve a real-world binary classification problem. The model successfully learns patterns from passenger data and predicts survival outcomes based on key passenger characteristics.
