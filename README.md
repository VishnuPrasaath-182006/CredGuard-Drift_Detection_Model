# 📊 CredGuard – Credit Risk Prediction & Drift Detection

## 🚀 Project Overview
CredGuard is a machine learning-based system designed to **predict credit risk** and **detect data drift** in financial datasets. It ensures that models remain reliable even when real-world data changes over time.

This project combines prediction with monitoring, making it closer to a **production-ready ML system**.

---

## 🎯 Problem Statement
Banks use machine learning models to approve or reject loans. However:
- Customer behavior and financial patterns change over time
- Model performance degrades due to **data drift**
- Static models fail in real-world scenarios

**Solution:**
- Predict whether a customer is **good or bad credit risk**
- Detect changes in incoming data using **drift detection techniques**

---

## 📂 Dataset
**German Credit Dataset**

- Contains 1000 customer records  
- Includes financial and personal attributes  
- Target:  
  - Good Credit  
  - Bad Credit  

Features include:
- Credit history  
- Loan amount  
- Duration  
- Employment status  
- Savings account  

---

## ⚙️ Tech Stack
- Python  
- NumPy, Pandas  
- Scikit-learn  
- XGBoost  
- Matplotlib
  
---

## 🧠 Models Used

### 1. Random Forest
- Ensemble model using multiple decision trees  
- Handles non-linear data effectively  

### 2. XGBoost
- Gradient boosting algorithm  
- High accuracy and optimized performance  

---

## 🔍 Drift Detection
Data drift occurs when the statistical properties of input data change over time.

In this project:
- Statistical methods (KS Test) are used  
- Feature distributions are compared  
- Drift is visualized for better understanding

---

## Data Visulisation
- CountPlot  
- Bar chart
- Correlation Matrix
- Histogram

---

## 📊 Workflow

```
Load Data → Preprocessing → Train/Test Split → Model Training → Evaluation → Drift Detection → Visualization
```

---

## 📈 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1 Score
  
---

## 🔗 Project Link
https://colab.research.google.com/github/VishnuPrasaath-182006/CredGuard-Drift_Detection_Model/blob/main/CredGuard.ipynb

---

## 💡 Key Features
- Credit Risk Prediction  
- Data Drift Detection  
- Model Comparison (Random Forest vs XGBoost)   
- Visualization of Data Changes  

---

## 📌 Future Improvements
- Deploy using FastAPI or Flask  
- Real-time drift monitoring  
- Automated retraining pipeline  
- Using SHAP (Explainable AI)
- Streamlit UI
- Adding Logistic Regression
- Using PSI Test
