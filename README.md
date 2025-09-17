# 📊 Telco Customer Churn Prediction System

Customer churn is one of the most pressing challenges in the telecom industry.  
This project builds a **Machine Learning model** to predict which customers are likely to churn, enabling proactive customer retention strategies.

---

## 📌 Project Overview
- Conducted **Exploratory Data Analysis (EDA)** to identify churn patterns.  
- Performed **data cleaning, preprocessing, and feature engineering**.  
- Handled **class imbalance** using SMOTE.  
- Trained and compared multiple ML models:  
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Support Vector Machine (SVM)  
  - K-Nearest Neighbors (KNN)  
- Achieved **~77% accuracy with Random Forest**, with strong recall for churned customers.  

---

## 🛠️ Tech Stack
- **Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, imbalanced-learn  
- **Environment:** Jupyter Notebook  

---

## 📈 Model Performance

| Model              | Accuracy | Precision | Recall | F1-Score |
|---------------------|----------|-----------|--------|----------|
| Logistic Regression | 72.9%    | 0.49      | 0.70   | 0.58     |
| Decision Tree       | 72.9%    | 0.49      | 0.60   | 0.54     |
| Random Forest       | **77.0%**| 0.56      | 0.66   | 0.60     |
| SVM                 | 73.7%    | 0.50      | 0.73   | 0.60     |
| KNN                 | 69.9%    | 0.46      | 0.70   | 0.56     |

---

## 🔍 Key Insights
- Customers with **month-to-month contracts** show higher churn rates.  
- Higher **monthly charges** correlate with increased churn probability.  
- Services like **Online Security** and **Tech Support** significantly reduce churn.  

---

## 📄 Project Report
The complete analysis (EDA → preprocessing → modeling → evaluation) is documented in the PDF.  

👉 [View Project Report](https://drive.google.com/file/d/1qiUnwfYvtm45IGSH5ny_zuMjp4W-9W5G/view?usp=sharing) 

---

