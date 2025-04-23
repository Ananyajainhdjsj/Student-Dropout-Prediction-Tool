# Student Dropout Prediction Tool 🎓🚀

**A Machine Learning project to predict student dropout risk based on academic, financial, and demographic factors.**

---

## 📚 Project Summary

- Performed data cleaning, EDA, and feature engineering on 4400+ student records.
- Removed irrelevant "Enrolled" cases — focused only on "Graduate" vs "Dropout."
- Applied feature selection using **SelectKBest** with **ANOVA F-test**.
- Standardized features using **StandardScaler** for model readiness.
- Trained multiple models:
  - Gaussian Naive Bayes
  - Logistic Regression
  - Random Forest Classifier
  - Support Vector Classifier (SVC)
  - K-Nearest Neighbors (KNN)
- Compared models using **Accuracy**, **Precision**, **Recall**, **F1 Score**, and **AUC**.
- Built an interactive **Gradio app** for live prediction.
- Fine-tuned the dropout probability threshold for better real-world usage.

---

## 🧠 Selected Features

- Application mode
- Debtor
- Tuition fees up to date
- Gender
- Scholarship holder
- Age at enrollment
- Curricular units 1st sem (approved)
- Curricular units 1st sem (grade)
- Curricular units 2nd sem (approved)
- Curricular units 2nd sem (grade)

---

## 🏆 Model Performance (Comparison)

| Model               | Accuracy | Precision | Recall | F1 Score | AUC    |
|---------------------|----------|-----------|--------|----------|--------|
| Naive Bayes         | 85.12%   | 85.12%    | 85.12% | 85.12%   | 90.91% |
| Logistic Regression | 89.39%   | 89.39%    | 89.39% | 89.39%   | 92.04% |
| Random Forest       | **91.32%** | **91.51%** | **85.25%** | **88.27%** | **93.67%** |
| SVC                 | 89.94%   | 89.94%    | 89.94% | 89.94%   | 91.83% |
| KNN                 | 90.36%   | 90.36%    | 90.36% | 90.36%   | 92.98% |

✅ **Best Model: Random Forest Classifier**

---


## 🛠️ Libraries and Tools Used

- Python
- pandas
- numpy
- seaborn
- matplotlib
- scikit-learn
- gradio

---

## ✨ Key Highlights

- Achieved 90%+ performance across multiple models.
- Used real-world feature engineering techniques (feature selection + scaling).
- Developed a flexible pipeline for threshold tuning.
- Visualized ROC curves and performance metrics for model evaluation.

---



---

---
