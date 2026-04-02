# Income Classification using Machine Learning

## 📌 Project Overview
This project focuses on predicting whether an individual earns more than 50K per year using machine learning classification techniques. The analysis includes data preprocessing, exploratory data analysis (EDA), model training, evaluation, and interpretation of results.

---

## 🎯 Objective
The goal of this project is to:
- Build and compare multiple classification models
- Handle class imbalance in the dataset
- Identify key factors that influence income levels
- Select the best-performing model based on relevant metrics

---

## 📊 Dataset
The dataset contains demographic and work-related attributes such as:
- Age
- Education
- Occupation
- Hours worked per week
- Marital status
- Capital gain/loss

Target variable:
- Income (`<=50K` or `>50K`)

---

## 🔍 Exploratory Data Analysis (EDA)
- Distribution analysis of numerical features
- Categorical feature breakdown
- Bivariate analysis between income and key variables
- Correlation heatmap

Key insight:
- Income is influenced by multiple factors beyond education, including age, relationship status, and working hours.

---

## ⚙️ Models Used
The following models were trained and evaluated:
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest

---

## ⚖️ Handling Class Imbalance
The dataset showed imbalance in the target variable.

Technique used:
- **SMOTE (Synthetic Minority Oversampling Technique)**

This improved the model's ability to detect the minority class (`>50K`).

---

## 📈 Model Evaluation
Evaluation metrics used:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

### Final Model:
**Random Forest with SMOTE**

Key results:
- Improved recall for `>50K` class (~70%)
- Better balance between precision and recall
- More effective detection of high-income individuals

---

## 🔎 Confusion Matrix Insights
- Increased true positives (better detection of `>50K`)
- Reduced false negatives
- Slight increase in false positives (acceptable trade-off)

---

## 🌟 Feature Importance
Top influencing features:
- Age
- Relationship
- Marital status
- Hours per week
- Capital gain

Insight:
- Income is strongly influenced by life stage and socioeconomic factors, not just education.

---

## 🧠 Conclusion
Random Forest combined with SMOTE provided the best performance for this problem. While there is a trade-off between precision and recall, improving detection of the minority class was prioritized. This project demonstrates a complete machine learning workflow from data preprocessing to model interpretation.

---
## 💼 Business Impact

This model can be used in real-world scenarios such as:
- Financial institutions for loan risk assessment
- Marketing teams for customer segmentation
- Salary prediction and workforce analytics

By improving recall for high-income individuals (>50K), the model helps identify valuable customers more effectively, even if it introduces a slight increase in false positives.

---

## 🛠️ Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Scikit-learn
- Imbalanced-learn (SMOTE)

---

## 📁 Project Structure
📦 income-classification
┣ 📜 notebook.ipynb
┣ 📜 README.md
┗ 📊 dataset


---

## 🚀 Next Steps
- Hyperparameter tuning for Random Forest
- Try advanced models (XGBoost, Gradient Boosting)
- Deploy model as a simple web app

---

## 👤 Author
Alejandro Ramos Bojorquez
