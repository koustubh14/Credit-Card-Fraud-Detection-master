# 💳 Credit Card Fraud Detection

A Machine Learning project by **Koustubh Trivedi**  
📍 GitHub: [@koustubh14](https://github.com/koustubh14)

---

## 🧠 Project Overview
This project aims to detect fraudulent credit card transactions using advanced machine learning techniques.  
It analyzes transaction data and identifies anomalies that suggest fraudulent behavior.

---

## 📊 Dataset
- **Source:** Kaggle – Credit Card Fraud Detection Dataset  
- **Rows:** 284,807  
- **Fraudulent Transactions:** 492 (Highly Imbalanced)  
- **Features:** Time, Amount, and 28 anonymized PCA-transformed features.

---

## ⚙️ Technologies Used
- Python 🐍  
- Pandas & NumPy  
- Scikit-learn  
- Matplotlib & Seaborn  
- Logistic Regression / Random Forest / XGBoost  

---

## 🧩 Methodology
1. Data preprocessing & cleaning  
2. Exploratory Data Analysis (EDA)  
3. Handling data imbalance (SMOTE / Under-sampling)  
4. Model training and evaluation  
5. ROC-AUC curve analysis  
6. Comparison of multiple models  

---

## 📈 Model Evaluation Metrics
- Accuracy  
- Precision & Recall  
- F1 Score  
- ROC-AUC Curve  

---

## 🚀 Results
- **Best Model:** Random Forest Classifier  
- **ROC-AUC:** ~0.98  
- **Precision:** 0.97  
- **Recall:** 0.92  

---

## 💡 Key Learnings
- Importance of handling imbalanced datasets  
- Trade-off between recall and precision in fraud detection  
- Ensemble models provide strong robustness in real-world financial systems  

---

## 🧰 How to Run
```bash
# Clone the repository
git clone https://github.com/koustubh14/Credit-Card-Fraud-Detection.git
cd Credit-Card-Fraud-Detection

# Install dependencies
pip install -r requirements.txt

# Run Jupyter Notebook
jupyter notebook
