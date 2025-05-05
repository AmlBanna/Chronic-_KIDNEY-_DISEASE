# Chronic Kidney Disease (CKD) Prediction

A simple machine learning project to predict chronic kidney disease using patient data.

## 📌 Features
- Data preprocessing (handling missing values, encoding categorical features).
- Exploratory Data Analysis (EDA) with visualizations.
- Model training using **Logistic Regression** and **Random Forest**.

## 🛠 Technologies Used
- Python 3
- Libraries:
  - `pandas`, `numpy` for data manipulation.
  - `matplotlib`, `seaborn` for visualization.
  - `scikit-learn` for machine learning.

## 📂 Dataset
The dataset (`kidney_disease.csv`) contains 25 features (e.g., `sg`, `al`, `sc`) and a target column (`classification`).

## 🎯 Model Performance
### Confusion Matrix

### Metrics Summary
| Metric          | Class: No CKD | Class: CKD |
|-----------------|--------------|------------|
| **Precision**   | 1.00         | 0.98       |
| **Recall**      | 0.96         | 1.00       |
| **F1-Score**    | 0.98         | 0.99       |

**Overall Accuracy**: 98.75%
