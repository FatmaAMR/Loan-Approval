# Loan Approval Prediction (Accuracy ~98%)

## Problem Statement
The objective of this project is to build a machine learning model that predicts whether a loan application will be **Approved** or **Rejected** based on applicant information.  
This helps financial institutions automate decision-making, reduce processing time, and minimize risks.

---

## Dataset
- **Source:** Kaggle Loan Approval Dataset  
- **Shape:** 4269 rows × 13 columns  
- **Features:** Applicant demographics, income, loan amount, credit score, and asset values  
- **Target:** Loan Status (Approved / Rejected)

---

## Project Workflow / Phases
1. **Problem Definition & Data Understanding**  
2. **Data Cleaning & Preprocessing**  
   - Handling missing values, duplicates, and outliers  
   - Feature scaling and encoding categorical variables  
   - Balancing data with **SMOTE**  
3. **Exploratory Data Analysis (EDA)**  
   - Distribution plots, correlation heatmaps  
   - Categorical distributions  
4. **Model Training & Evaluation**  
   - Logistic Regression  
   - Random Forest  
   - XGBoost  
   - Evaluation using **Confusion Matrix, ROC-AUC, Classification Report**  
5. **Insights & Conclusion**  
   - Feature importance analysis  
   - Best-performing model selection  

---

## 📈 Models & Results
- **Logistic Regression:** Good baseline performance  
- **Random Forest:** Robust and interpretable model  
- **XGBoost:** Best performance with highest accuracy and ROC-AUC  

| Model                | Accuracy | ROC-AUC |
|-----------------------|----------|---------|
| Logistic Regression   | ~96%     | ~0.97   |
| Random Forest         | ~98%     | ~0.98   |
| XGBoost              | ~98%     | ~0.99   |

---

## Tech Stack
- Python 
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- imbalanced-learn (SMOTE)  
- XGBoost  

---

## Sample Visuals
<img width="687" height="574" alt="image" src="https://github.com/user-attachments/assets/7c4cb912-7875-4bd0-a8fa-7667254c0262" />

<img width="776" height="561" alt="image" src="https://github.com/user-attachments/assets/9fecf57e-9509-410d-b268-5e65c15f8e26" />
  
<img width="786" height="456" alt="image" src="https://github.com/user-attachments/assets/ad41ae4e-70da-44c6-8dc1-c1a112b54ce3" />

