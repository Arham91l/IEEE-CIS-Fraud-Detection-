# 🔍 IEEE-CIS Fraud Detection

A machine learning project to detect fraudulent financial transactions using the IEEE-CIS Fraud Detection dataset.

## 📌 Problem Statement
Financial fraud causes billions in losses annually. This project builds an intelligent ML pipeline to detect fraudulent transactions using transactional and identity-related behavioral patterns.

## 📊 Dataset
- **Source:** IEEE-CIS Fraud Detection (Kaggle)
- **Size:** 590K+ transactions
- **Features:** 400+ transactional and identity features
- **Target:** isFraud (0 = Legitimate, 1 = Fraud)

## 🔧 Tech Stack
- Python, Pandas, NumPy
- Scikit-learn, XGBoost, LightGBM
- Imbalanced-learn (SMOTETomek)
- SHAP (Explainability)
- Matplotlib, Seaborn

## 🚀 Pipeline
1. Data Loading & Merging
2. Missing Value Handling
3. Feature Engineering
4. Categorical Encoding
5. Imbalance Handling (SMOTETomek)
6. Model Training (RF, XGBoost, LightGBM)
7. Evaluation (ROC-AUC, PR-AUC, F1)
8. Explainability (SHAP)

## 📈 Results
| Model | ROC-AUC | PR-AUC | Precision | Recall |
|-------|---------|--------|-----------|--------|
| Random Forest | 0.953 | 0.833 | 0.89 | 0.66 |
| **XGBoost** | **0.973** | **0.885** | **0.90** | **0.73** |
| LightGBM | 0.967 | 0.859 | 0.88 | 0.70 |

✅ **XGBoost selected as best model**

## 💼 Business Impact
- Earlier fraud detection
- Reduced financial losses
- Improved transaction monitoring
- Explainable AI for compliance

## 👤 Author
Shaikh Arham Ahmed —  https://github.com/Arham91l
