# ❤️ Heart Disease Prediction using Logistic Regression

This project was completed as part of the **AI/ML Engineering Internship at DevelopersHub Corporation**.

##  Objective

To build a machine learning model that predicts whether a person is at risk of heart disease based on medical attributes.

---

##  Dataset

- Heart Disease UCI Dataset
- Source: Kaggle
- Total Records: 920
- Features: 16 medical attributes

---

##  Project Workflow

### 1️⃣ Data Cleaning
- Handled missing values
- Converted categorical variables using encoding
- Removed unnecessary columns (e.g., id)

### 2️⃣ Exploratory Data Analysis (EDA)
- Feature distribution analysis
- Correlation analysis
- Visualization using matplotlib and seaborn

### 3️⃣ Model Training
- Algorithm Used: Logistic Regression
- Train-Test Split: 80-20

### 4️⃣ Model Evaluation

| Metric | Score |
|--------|--------|
| Accuracy | 91.6% |
| ROC-AUC Score | 0.94 |
| Precision | 88% |
| Recall | 92% |

Confusion Matrix Results:

- True Positive (TP): 23
- True Negative (TN): 32
- False Positive (FP): 3
- False Negative (FN): 2

The high recall (92%) indicates that the model effectively identifies patients at risk, which is critical in medical diagnosis.

---

## 📈 ROC Curve

The ROC curve demonstrates strong model performance with an AUC score of 0.94, indicating excellent classification capability.

---

## 🛠️ Tools & Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

##  Key Insights

- Chest pain type, thal, ca, and oldpeak were important features.
- Logistic Regression performed well for binary classification.
- The model can be used for early heart disease risk screening.

---

##  Conclusion

The Logistic Regression model achieved strong predictive performance and demonstrates its usefulness in medical risk prediction scenarios.

---

##  Author

Ali Raza  
AI/ML Engineering Intern  
DevelopersHub Corporation
