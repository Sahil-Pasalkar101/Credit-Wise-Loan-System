# Credit-Wise-Loan-System
<b>Credit-Wise Loan Prediction Model<b> is a machine learning project designed to assess loan eligibility and predict the likelihood of loan approval based on applicant data. The model analyzes various financial and personal attributes to assist in smarter and faster credit decision-making.
This project demonstrates a complete ML workflow, including data analysis, preprocessing, model building, and evaluation.

---

## Project Workflow
- Conducted **Exploratory Data Analysis (EDA)** to identify patterns and key insights  
- Handled missing values using **SimpleImputer**  
- Applied **encoding techniques** for categorical variables  
- Performed **feature scaling** on numerical data  
- Trained a **Random Forest Classifier**  
- Evaluated model performance using classification metrics  
---

## Model Performance:

| Class | Precision | Recall | F1-Score | Support |
|-------|----------|--------|----------|---------|
| 0 (Rejected) | 0.92 | 0.95 | 0.93 | 135 |
| 1 (Approved) | 0.89 | 0.83 | 0.86 | 65 |

---

## Overall Metrics

| Metric | Value |
|--------|-------|
| Accuracy | 0.91 |
| Macro Avg Precision | 0.90 |
| Macro Avg Recall | 0.89 |
| Macro Avg F1-Score | 0.90 |
| Weighted Avg F1-Score | 0.91 |

**Key Observations:**
- Achieved **91% accuracy**  
- Strong performance in identifying loan rejections  
- Slightly lower recall for loan approvals  

---

## 🛠️ Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---
