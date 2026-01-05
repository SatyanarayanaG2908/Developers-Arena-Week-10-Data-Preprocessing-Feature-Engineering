# 👥 Customer Churn Prediction – Data Preprocessing & Feature Engineering

## 📌 Project Overview
This project focuses on **data preprocessing and feature engineering** for a **Customer Churn Prediction** problem.  
The goal is to prepare raw customer data, engineer meaningful features, and build a complete preprocessing pipeline that can be directly used for machine learning models to predict whether a customer is likely to leave (churn).

This project is part of **Week 10: Data Preprocessing & Feature Engineering**.

---

## 🎯 Project Objectives
- Handle categorical and numerical data effectively  
- Apply multiple encoding techniques  
- Perform feature scaling using different methods  
- Detect and handle outliers  
- Engineer new meaningful features  
- Select important features  
- Build an end-to-end preprocessing pipeline  
- Prepare data for churn prediction modeling  


---

## 📊 Dataset Information
- **Dataset Name:** Customer Churn Dataset  
- **Rows:** ~500  
- **Columns:** 4+ (expanded after feature engineering)  
- **Target Variable:** `Churn`  

### Original Features
- customerID  
- tenure  
- MonthlyCharges  
- TotalCharges  
- Contract / Payment / Services (categorical)

---

## 🧠 Concepts Covered
- Categorical Data Handling  
- Feature Encoding  
- Feature Scaling  
- Outlier Detection  
- Feature Engineering  
- Feature Selection  
- Pipeline Creation  

---

## ⚙️ Encoding Techniques Used
1. **Label Encoding** – Target variable (Churn)  
2. **One-Hot Encoding** – Categorical features  
3. **Binary Encoding** – Engineered binary features  

---

## 📏 Feature Scaling Techniques
- **Min-Max Scaling**
- **Standard Scaling**

---

## 🚨 Outlier Detection Methods
- **Interquartile Range (IQR) Method**
- **Z-Score Method**

Outliers are removed to improve model stability and performance.

---

## 🛠️ Feature Engineering (5+ Features)
The following new features are created:
- Average Charges per Month  
- Charge Ratio  
- Customer Lifetime Value  
- Long-Term Customer Flag  
- High Monthly Charges Indicator  

These features help capture customer behavior more effectively.

---

## 🔍 Feature Selection
- **SelectKBest (Chi-Square Test)** is used  
- Top features are selected based on statistical importance  

---

## 🔗 Preprocessing Pipeline
A complete pipeline is built using `scikit-learn` that includes:
- Encoding
- Scaling
- Feature Selection
- Model Training

This ensures consistency, reusability, and clean workflow.

---

## 🤖 Model Used
- **Logistic Regression**

The model is trained on the fully processed data to predict customer churn.

---

## 📈 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score

A classification report is generated for performance analysis.

---

## 🚀 How to Run the Project
1. Open `churn_prediction_pipeline.ipynb` in Google Colab  
2. Run all cells (single-cell implementation available)  
3. View model performance metrics  
4. Download `processed_churn_data.csv`  

---
## 📚 Learning Resources
- YouTube: *Feature Engineering for Machine Learning*  
- scikit-learn Documentation  
- Kaggle Customer Churn Datasets  

---

## ✅ Conclusion
This project demonstrates a complete and structured approach to **data preprocessing and feature engineering** for machine learning. It prepares raw customer data into a clean, meaningful, and model-ready format while ensuring reproducibility and clarity. The project builds a strong foundation for advanced predictive modeling and real-world data science applications.

---
## Author
**Sri Venkata Satyanarayana Gattu**

