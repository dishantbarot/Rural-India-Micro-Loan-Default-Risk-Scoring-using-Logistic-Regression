 # Rural India Micro-Loan Default Risk Scoring using Logistic Regression  

---

## ⭐ S — Situation  

Microfinance institutions and rural NBFCs in India face significant credit risk due to income volatility, regional economic instability, and borrower repayment behavior.  

Traditional lending decisions often rely on manual assessment, leading to inconsistent risk evaluation and higher Non-Performing Assets (NPAs).

There is a need for a data-driven risk scoring system to predict micro-loan default probability.

---

## 🎯 T — Task  

Develop a machine learning-based binary classification model to:

- Predict loan default (0/1)
- Identify high-risk borrowers
- Quantify financial risk drivers
- Build a reproducible fintech-grade ML pipeline

---

## ⚙️ A — Action  

### 📊 1. Data Understanding & EDA
- Analyzed income distribution and loan exposure
- Checked class imbalance
- Correlation analysis
- Risk distribution visualization

### 🛠 2. Feature Engineering
- Debt-to-Income Ratio (DTI)
- Income segmentation bands
- Ordinal encoding of repayment history

### 📏 3. Data Preprocessing
- StandardScaler normalization
- Stratified Train-Test split
- 5-Fold Cross Validation

### 🎯 4. Feature Selection
- Recursive Feature Elimination (RFE)
- L1 Regularization

### 🤖 5. Model Development
- Logistic Regression (Baseline Credit Risk Model)
- Probability-based risk scoring

### 📈 6. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Curve

---

## 📊 R — Result  

- Achieved strong ROC-AUC performance
- Identified key risk drivers:
  - High Debt-to-Income Ratio
  - High Village Risk Score
  - Poor Repayment History
- Built a scalable and interpretable credit risk scoring system

This model structure mirrors real-world microfinance underwriting systems.

---

## 📁 Dataset Overview  

| Feature | Description |
|----------|------------|
| Income_INR | Monthly borrower income |
| Village_Risk_Score | Regional economic risk |
| Loan_Size_INR | Sanctioned loan amount |
| Past_Repayment_History | Credit behavior indicator |
| DTI | Debt-to-Income ratio |
| Default | Target variable |

Records: 10,000 rural borrowers  

---

## 🧠 Tech Stack  

- Python  
- Pandas  
- NumPy  
- Scikit-Learn  
- Matplotlib  
- Seaborn  
