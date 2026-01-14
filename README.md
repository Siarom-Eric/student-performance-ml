# 🎓 Student Performance Prediction with Machine Learning

## 📌 Project Overview

This project applies **machine learning and data science methodologies** to predict students' final academic performance (final grade `G3`) based on socio‑economic, academic and personal factors.

The work follows a **scientific and structured workflow**, including exploratory data analysis, data preprocessing, feature engineering, model training, cross‑validation, hyperparameter tuning and evaluation.

---

## 🎯 Objective

Build and evaluate regression models capable of predicting students' final grades, while also understanding which factors most influence academic performance.

---

## 📊 Dataset

* Source: OpenML – *Student Performance Dataset* (ID: 40984)
* Data from two Portuguese secondary schools
* Includes variables related to:

  * Study habits
  * Family background
  * Parental education
  * Alcohol consumption
  * School support
  * Previous grades

The dataset is loaded directly via:

```python
from sklearn.datasets import fetch_openml
```

---

## 🧠 Problem Type

This is treated as a **supervised regression problem**, since the target variable `G3` (final grade) is continuous (0–20).

Models explored include:

* Linear Regression
* Ridge Regression
* Random Forest Regressor
* Gradient Boosting Regressor

---

## ⚙️ Project Workflow

The notebook follows a structured data science pipeline:

* Data loading and initial inspection
* Data quality checks (missing values, data types)
* Exploratory Data Analysis (EDA)
* Statistical analysis of variables
* Visualization of distributions and boxplots
* Feature engineering and preprocessing

  * One-hot encoding of categorical variables
  * Robust scaling
* Train/test split
* Pipeline construction using scikit-learn
* Cross-validation (Repeated K-Fold)
* Hyperparameter tuning (RandomizedSearchCV)
* Model evaluation using:

  * R²
  * MAE
  * MSE
* Learning curves analysis
* Feature importance analysis (permutation importance)

---

## 📈 Key Outcomes

* Comparison of multiple regression models
* Identification of the most relevant features influencing student performance
* Clear trade-off analysis between model complexity and interpretability

> Note: This project focuses on methodological rigor and learning outcomes rather than maximizing leaderboard-style performance.

---

## 🛠️ Technologies Used

* Python
* Pandas, NumPy
* Scikit-learn
* Matplotlib, Seaborn
* Jupyter Notebook

---

## 📌 Example Results
Best model achieved:
- R²: 0.32
- MAE: 1.90

---

## 🚀 How to Run

```bash
pip install -r requirements.txt
jupyter notebook
```

Open the notebook and run the cells sequentially.

---

## 👤 Author

Eric Morais
