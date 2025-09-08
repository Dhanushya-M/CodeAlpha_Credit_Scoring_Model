# 💳 German Credit Risk Prediction

## 📌 Overview
This project predicts **creditworthiness of loan applicants** using the **German Credit Dataset**.  
It applies **Machine Learning classification models** to determine whether an applicant is a **Good Credit** (1) or **Bad Credit** (0) risk.  

---
## ⚙️ Features
- ✅ Data Preprocessing (missing values, encoding categorical features, scaling)  
- ✅ Exploratory Data Analysis (EDA) with visualizations  
- ✅ Model Training with Logistic Regression, Decision Trees, Random Forest, XGBoost  
- ✅ Hyperparameter Tuning using GridSearchCV  
- ✅ Model Evaluation (Accuracy, Confusion Matrix, Classification Report)  
- ✅ Test Prediction on New Applicants  
- ✅ Ready-to-use Google Colab Notebook  
---
## 📂 Dataset
- **Source:** [UCI German Credit Data](https://archive.ics.uci.edu/ml/datasets/statlog+(german+credit+data))  
- **File:** `german_credit_data.csv`  
- **Target Column:** `kredit`  
  - `1 = Good Credit`  
  - `2 = Bad Credit`  
---
## 🛠️ Tech Stack
- Python 3.x  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- XGBoost  
---
## 🚀 How to Run

### 1️⃣ Clone Repository
```bash
git clone https://github.com/<your-username>/German-Credit-Risk-Prediction.git
cd German-Credit-Risk-Prediction

2️⃣ Install Dependencies
pip install -r requirements.txt

3️⃣ Open Notebook
jupyter notebook notebooks/credit_risk_model.ipynb


or run on Google Colab.

📊 Results

Random Forest achieved the best performance with high accuracy.

Key influencing factors: laufkont (account balance), hoehe (loan amount), alter (age), and beszeit (employment history).

🔮 Future Work

Deploy as a Flask/Django Web App for loan officers.

Use SHAP values / LIME for explainable AI.

Explore Deep Learning (ANN) for credit scoring.

👩‍💻 Author

Your Name

🌐 LinkedIn

📧 your.email@example.com

---
# 📌 requirements.txt
```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
xgboost
