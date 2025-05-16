# ❤️ Coronary Heart Disease Prediction Using Logistic Regression (R)

This project explores the **application of logistic regression** to predict the presence of **Coronary Heart Disease (CHD)** using medical variables from the **UCI Heart Disease dataset**. It was implemented as part of an academic research submission for the M.Sc. Statistics program at Kannur University.

---

## 📊 Project Overview

- **Objective**: To build a predictive model for diagnosing heart disease and identify the most significant risk factors.
- **Methodology**: Logistic Regression using R programming.
- **Dataset**: UCI Heart Disease (Cleveland subset).

---

## 🧪 Tools & Technologies

- **Language**: R
- **Packages Used**:  
  - `ggplot2` for visualization  
  - `dplyr` for data manipulation  
  - `car`, `ResourceSelection` for diagnostics  
  - `pROC` for ROC Curve Analysis

---

## 🧬 Dataset Details

- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/heart+Disease)
- **Records Used**: 297 (cleaned from original 303)
- **Target Variable**: `hd` (0 = healthy, 1 = heart disease)
- **Key Features**:
  - Age
  - Sex
  - Chest Pain Type
  - Resting Blood Pressure
  - Serum Cholesterol
  - Fasting Blood Sugar
  - Resting ECG
  - Maximum Heart Rate Achieved
  - Exercise-Induced Angina
  - ST Depression
  - Thalassemia
  - Number of Major Vessels

---

## 🔍 Analysis Highlights

### ✅ Significant Risk Factors Identified:
- **Age**: Risk increases with age.
- **Sex**: Males are more likely to have heart disease.
- **Chest Pain Type**: Type 4 (asymptomatic) has the strongest association.
- **Resting ECG**: Abnormal results strongly correlate with heart disease.
- **Maximum Heart Rate**: Inverse relationship—lower heart rate indicates higher risk.

### ❌ Non-significant Factors:
- Fasting Blood Sugar
- Serum Cholesterol
- Resting Blood Pressure

---

## 🧠 Statistical Methods Used

- **Binary Logistic Regression**
- **Odds & Odds Ratio Calculations**
- **Stepwise Variable Selection**
- **Hosmer-Lemeshow Goodness-of-Fit Test**
- **Classification Accuracy Table**
- **Area Under ROC Curve (AUC)**

---

## 📈 Model Performance

- **ROC Curve AUC**: Demonstrated strong discriminative power.
- **Hosmer-Lemeshow Test**: Good model fit.
- **Classification Table**: High predictive accuracy observed during validation.

---

## 📚 Key Learning Outcomes

- Applied GLM theory using R
- Interpreted odds ratios and regression coefficients in medical context
- Evaluated model accuracy with proper statistical diagnostics
- Gained experience in R-based EDA and predictive modeling

---

## 👩‍💻 Author

**Fathimath Shamrin M A**  
M.Sc. Statistics (2017–2019)  
Kannur University  
Nehru Arts & Science College, Kanhangad

---

## 📁 Project Files

- Project Report (PDF)
- R Scripts (not included here—available upon request)
- Figures and Visualizations

---

## 📌 Citation

> "Application of Logistic Regression in Prediction of Coronary Heart Disease", M.Sc. Project, 2019.
