# FraudShield – Credit Card Fraud Detection System  

## 📌 Overview  
Fraudulent credit card transactions are a major challenge for the financial industry, leading to significant losses and reduced customer trust. **FraudShield** is a machine learning project that leverages **Logistic Regression, Random Forest, and XGBoost** to detect fraudulent transactions with high accuracy.  

---

## 🎯 Objectives  
- Perform **Exploratory Data Analysis (EDA)** to understand transaction patterns and class imbalance.  
- Preprocess the dataset (scaling, handling imbalance with **SMOTE**).  
- Build and evaluate multiple models:  
  - **Logistic Regression** (baseline)  
  - **RandomForestClassifier** (ensemble approach)  
  - **XGBClassifier** (gradient boosting)  
- Compare performance across models using:  
  - **Precision, Recall, F1-score, ROC-AUC**  
- Visualize results with **confusion matrices, ROC curves**.  

---

## 📂 Project Structure 
FraudShield-CreditCardFraudDetection/
│
├── data/
│ └── creditcard.csv
│
├── notebook/
│ └── fraudshield_notebook.ipynb
│
├── README.md
└── requirements.txt

---

## 🛠 Tech Stack  
- **Language:** Python  
- **Libraries:**  
  - `pandas`, `numpy` → data manipulation  
  - `matplotlib`, `seaborn` → visualization  
  - `scikit-learn` → preprocessing, evaluation  
  - `xgboost` → XGBClassifier for boosting  
  - `imbalanced-learn` → SMOTE for handling imbalance
- **Environment:** Jupyter Notebook  

--- 

## 📊 Dataset 
- **Source:** [Kaggle – Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)

---

## 📈 Results  

- Logistic Regression achieved high recall but very low precision, meaning it detected most frauds but also raised many false alarms.  
- Random Forest provided excellent precision and overall accuracy, but recall was slightly lower compared to Logistic Regression.  
- XGBoost offered the best balance between precision and recall, delivering the most reliable performance for fraud detection.  
- Overall, ensemble methods (Random Forest and XGBoost) outperformed Logistic Regression, with XGBoost emerging as the most effective model.  

---

## 🚀 How to Run  

```bash
# Clone repository
git clone https://github.com/swatighegde/datascience-kit.git
cd FraudShield

# Launch notebook
jupyter notebook credit_card_fraud_detection.ipynb