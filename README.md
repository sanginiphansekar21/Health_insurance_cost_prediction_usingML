# 🏥 Health Insurance Cost Prediction using Machine Learning

## 📌 Project Overview

This project predicts health insurance payment amounts based on customer attributes such as age, BMI, blood pressure, smoking habits, diabetic condition, and number of children.

It demonstrates an **end-to-end Machine Learning pipeline** — from data preprocessing and model training to deployment using Streamlit.

---

## 🎯 Business Problem

Insurance companies need accurate cost prediction models to:

- Minimize underwriting risk  
- Improve premium pricing strategy  
- Increase operational efficiency  
- Enable data-driven decision making  

This project builds a regression model to solve this problem effectively.

---

## ✨ Key Features

✔ Data Cleaning & Preprocessing  
✔ Exploratory Data Analysis (EDA)  
✔ Feature Engineering  
✔ Label Encoding for Categorical Variables  
✔ Feature Scaling using StandardScaler  
✔ Multiple Model Comparison  
✔ Model Evaluation (R², MAE, RMSE)  
✔ Best Model Selection  
✔ Streamlit Web Application  
✔ Real-time Prediction  

---

## 🛠 Tech Stack

**Programming & Analysis**
- Python
- Pandas
- NumPy

**Machine Learning**
- Scikit-learn
- StandardScaler
- LabelEncoder
- Joblib

**Visualization**
- Matplotlib
- Seaborn

**Deployment**
- Streamlit

---

## 🤖 Machine Learning Details

- Problem Type: Regression
- Models Tested:
  - Linear Regression
  - Random Forest Regressor
  - Gradient Boosting Regressor
- Best Model Selected Based On:
  - Highest R² Score
  - Lowest MAE
  - Lowest RMSE

---

## 📊 Data Pipeline

1. Data Cleaning  
2. Handling Categorical Variables  
3. Feature Scaling  
4. Model Training  
5. Model Evaluation  
6. Model Serialization using Joblib  
7. Streamlit Deployment  

---

## 📂 Project Structure

Health_insurance_cost_prediction_usingML/

│── app.py  
│── best_model.pkl  
│── scaler.pkl  
│── label_encoder_gender.pkl  
│── label_encoder_smoker.pkl  
│── label_encoder_diabetic.pkl  
│── requirements.txt  
│── analysis_notebook.ipynb  
│── README.md  

---

## 🚀 How to Run Locally

1. Clone the repository:

```
git clone <your-repo-link>
```

2. Navigate to project folder:

```
cd Health_insurance_cost_prediction_usingML
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Run the application:

```
python -m streamlit run app.py
```

---

## 📈 Business Impact

This solution helps:

- Improve pricing accuracy  
- Reduce financial uncertainty  
- Automate cost estimation  
- Support data-driven insurance decisions  

