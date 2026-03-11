# ❤️ Heart Disease Prediction using Machine Learning

This project is an **end-to-end Machine Learning application** that predicts the likelihood of heart disease based on patient health parameters.  

It includes **data preprocessing, exploratory data analysis (EDA), model training, evaluation, and deployment using Streamlit**.

The objective of this project is to demonstrate the complete **machine learning workflow from data analysis to model deployment**.

---
 
## 📸 Application Screenshot

<p align="center">
  <img width="610" height="998" alt="image" src="https://github.com/user-attachments/assets/a5954042-f7a3-4671-b82d-cca00ec6c77d" />

  <img width="634" height="1009" alt="image" src="https://github.com/user-attachments/assets/b38a3b11-4598-4adb-91e2-13b7ebc7d730" />

</p>

---

## 📊 Project Overview

Heart disease is one of the leading causes of death worldwide. Early prediction can help in preventive healthcare.

This project uses health-related attributes such as:

- Age
- Sex
- Resting Blood Pressure
- Cholesterol
- Maximum Heart Rate
- Chest Pain Type
- Fasting Blood Sugar
- Oldpeak and other medical indicators

Using these features, machine learning models are trained to predict whether a patient is likely to have heart disease.

---

## 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Streamlit

---

## 📂 Project Workflow

### 1️⃣ Data Loading
The dataset is loaded using Pandas and basic information about the dataset is explored.

### 2️⃣ Data Cleaning
- Checked for missing values
- Checked for duplicate records
- Replaced invalid values such as **0 cholesterol and 0 resting blood pressure** with the mean.

### 3️⃣ Exploratory Data Analysis (EDA)

Visualizations were created to understand patterns in the data.

Examples include:

- Age distribution
- Cholesterol distribution
- Heart disease count
- Gender vs heart disease
- Chest pain type analysis
- Correlation heatmap

---

### 4️⃣ Data Preprocessing

- Categorical variables encoded using **One Hot Encoding**
- Feature scaling applied using **StandardScaler**

---

### 5️⃣ Model Training

Multiple machine learning models were trained and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)

---

### 6️⃣ Model Evaluation

Models were evaluated using:

- Accuracy Score
- F1 Score
- Confusion Matrix
- Classification Report

---

### 7️⃣ Model Export

The best performing model was saved using **Joblib**.
```
Saved files:
KNN_Heart.pkl
scaler.pkl
columns.pkl
```

These files are used for prediction in the deployed application.

---

## 🌐 Web App Deployment

The trained model is deployed as an interactive web application using **Streamlit**.

Users can enter health parameters and instantly get predictions about the likelihood of heart disease.

---

## 📁 Project Structure

```
Heart-Disease-Prediction
│
├── heart.csv
├── heart_disease_model.ipynb
├── app.py
├── KNN_Heart.pkl
├── scaler.pkl
├── columns.pkl
├── screenshots
│   └── app_screenshot.png
└── README.md
```

## 🚀 How to Run the Project

### 1️⃣ Clone the repository
git clone https://github.com/MiteshBhoir/Heart-Disease-Prediction-ML-Classification.git

---

## 📈 Future Improvements

- Improve model performance with advanced algorithms
- Add more datasets
- Deploy using cloud platforms
- Add interactive dashboards

---

## 🎯 Learning Outcomes

Through this project I learned:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Machine learning model training
- Model evaluation techniques
- Model deployment using Streamlit

---

⭐ If you like this project, consider giving it a **star on GitHub**.
