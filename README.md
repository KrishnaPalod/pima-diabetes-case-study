# Statistical Insights into Diabetes Risk: An Inferential Study Using the Pima Indians Dataset

This repository contains the complete case study for the course **21AIC401T – Inferential Statistics and Predictive Analytics**.  
The project applies inferential statistics to the **Pima Indians Diabetes Dataset** to explore how clinical variables relate to diabetes risk.  

---

## 📊 Dataset
- **Name:** Pima Indians Diabetes Database  
- **Source:** [UCI Repository](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database?resource=download) / Kaggle  
- **Records:** 768 adult women (≥21 years), Pima Indian heritage  
- **Variables used in analysis:**  
  - *Glucose (mg/dL)*  
  - *BMI (kg/m²)*  
  - *Age (years)* – categorized into Young (≤30), Middle (31–50), Old (>50)  
  - *Outcome* – 0 = Non-diabetic, 1 = Diabetic  

---

## 🧪 Tests Performed

### 1. One-Sample t-test (Glucose vs WHO 126 mg/dL)
- **Problem Statement:** Is the mean fasting glucose significantly different from the WHO cutoff of 126 mg/dL?  
- **Result:** Mean = 120.9 mg/dL, t(767) = -4.43, p < 0.001.  
- **Interpretation:** The average glucose is significantly lower than the WHO threshold, though many individuals exceed it.  

---

### 2. Two-Sample Welch t-test (BMI by Diabetes Outcome)
- **Problem Statement:** Does BMI differ between diabetic and non-diabetic women?  
- **Result:** Non-diabetic mean BMI = 30.3, Diabetic mean BMI = 35.1, t = -8.62, p < 0.001.  
- **Interpretation:** Diabetic women have significantly higher BMI, confirming obesity as a strong risk factor.  

---

### 3. One-Way ANOVA (Glucose by Age Group)
- **Problem Statement:** Do glucose levels differ across age groups (≤30, 31–50, >50)?  
- **Result:** F(2,765) = 28.00, p < 0.001.  
- **Tukey HSD Post-hoc:** All three groups (Young, Middle, Old) differ significantly.  
- **Interpretation:** Glucose levels increase with age.  

---


