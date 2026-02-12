# 🛡️ Machine Failure Prediction using Machine Learning

## 📌 Project Overview
This project focuses on predicting machine failures using machine learning techniques. By analyzing operational data, the model identifies patterns that indicate potential failures, helping organizations take preventive actions and reduce downtime.

---

## 🎯 Objectives
- Perform data cleaning and preprocessing  
- Handle class imbalance using SMOTE  
- Train a robust classification model  
- Evaluate performance using multiple metrics  
- Interpret model decisions with SHAP  
- Save and reload the trained model for future predictions  

---

## 🗂️ Dataset
The dataset contains machine-related features such as operational conditions and failure indicators.

**Key Steps Performed:**
- Removed irrelevant columns  
- Encoded categorical variables  
- Checked class distribution  
- Balanced the dataset using SMOTE  

---

## ⚙️ Technologies Used
- **Python**
- **Pandas & NumPy** – Data manipulation  
- **Matplotlib & Seaborn** – Visualization  
- **Scikit-learn** – Model building & evaluation  
- **Imbalanced-learn (SMOTE)** – Handling class imbalance  
- **SHAP** – Model explainability  

---

## 🚀 Project Workflow
1. Import required libraries  
2. Load and explore the dataset  
3. Clean and preprocess the data  
4. Encode categorical features  
5. Split data into training and testing sets  
6. Apply SMOTE to balance classes  
7. Train a Random Forest classifier  
8. Evaluate model performance (confusion matrix, ROC curve, cross-validation)  
9. Analyze feature importance  
10. Explain predictions using SHAP  
11. Save and reload the trained model  

---

## 📊 Model Performance
The Random Forest model was used for classification and evaluated using:

- Accuracy  
- Precision  
- Recall  
- F1-score  
- ROC Curve  
- Cross-validation  

These metrics ensure the model is reliable and generalizes well to unseen data.

---

## 🔍 Model Explainability
SHAP (SHapley Additive exPlanations) was implemented to understand how each feature contributes to predictions, improving transparency and trust in the model.

---

## 💾 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone <your-repo-link>
cd <repo-folder>
