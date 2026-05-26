<div align="center">

# 🚢 Titanic Survival Prediction using Machine Learning

### *End-to-End Supervised Machine Learning Classification Project*

<br>

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?style=for-the-badge&logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)

</div>

---

# 📌 Project Overview

This project aims to predict passenger survival on the Titanic using multiple supervised Machine Learning classification algorithms.

The project follows a complete Machine Learning workflow including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Feature selection
- Model training
- Hyperparameter tuning
- Overfitting / Underfitting analysis
- Model comparison
- Visualization and interpretation

The dataset used is the famous **Titanic - Machine Learning from Disaster** dataset from Kaggle.

---

# 📂 Dataset

🔗 Dataset Source:  
https://www.kaggle.com/competitions/titanic

The dataset contains passenger information such as:

| Feature | Description |
|---|---|
| `Pclass` | Passenger class |
| `Sex` | Gender |
| `Age` | Passenger age |
| `Fare` | Ticket fare |
| `Parch` | Parents / children aboard |
| `SibSp` | Siblings / spouses aboard |
| `Embarked` | Port of embarkation |

### 🎯 Target Variable

```python
Survived
```

- `1` → Survived
- `0` → Did not survive

---

# ⚙️ Machine Learning Workflow

## 1️⃣ Data Cleaning

- Missing value handling
- Age imputation
- Cabin removal
- Encoding categorical variables

---

## 2️⃣ Feature Engineering

New features were created:

```python
FamilySize
IsAlone
```

---

## 3️⃣ Feature Selection

Feature importance analysis was performed using:

- SelectKBest
- Chi-Square Test

Final selected features:

```python
['Pclass', 'Sex', 'Age', 'Parch', 'Fare', 'IsAlone']
```

---

# 🤖 Machine Learning Models

The following classification algorithms were implemented and compared:

| Model | Category |
|---|---|
| Logistic Regression | Linear Model |
| Decision Tree | Tree-Based |
| Random Forest | Ensemble Learning |
| Support Vector Machine (SVM) | Margin-Based |
| K-Nearest Neighbors (KNN) | Distance-Based |
| XGBoost | Gradient Boosting |

---

# 📊 Model Evaluation

The models were evaluated using:

| Metric | Purpose |
|---|---|
| Accuracy Score | Overall performance |
| Confusion Matrix | Error analysis |
| Classification Report | Precision / Recall / F1-score |
| Feature Importance | Identify influential variables |
| Learning Curves | Detect overfitting and underfitting |

---

# 📈 Visualizations

## 🔹 Model Accuracy Comparison

![Model Comparison](image/Model%20Accuracy%20Comparison.png)

---

## 🔹 Decision Tree Visualization

![Decision Tree](image/decision_tree.png)

---

## 🔹 KNN Accuracy Curve

![KNN Curve](image/KNN:%20Accuracy%20vs%20K.png)

---

## 🔹 SVM Overfitting vs Underfitting Analysis

![SVM Curve](image/svm_overfitting_curve.png)

---

## 🔹 XGBoost Feature Importance

![XGBoost Importance](image/Feature%20Importance%20-%20XGBoost.png)

---

# 🧠 Key Machine Learning Concepts Explored

This project explores several important Machine Learning concepts:

- Classification algorithms
- Bias vs Variance tradeoff
- Overfitting and Underfitting
- Hyperparameter tuning
- Ensemble Learning
- Gradient Boosting
- Feature Importance
- Model Generalization

---

# 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Analysis |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| XGBoost | Gradient Boosting |

---

# 📁 Project Structure

```bash
titanic-ml-classification/
│
├── data/
├── image/
├── notebooks/
│   └── titanic_classification.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# 🚀 Installation

## Clone the repository

```bash
git clone https://github.com/maaarouaane/titanic-ml-classification.git
```

---

## Install dependencies

```bash
pip install -r requirements.txt
```

---

## Launch Jupyter Notebook

```bash
jupyter notebook
```

---

# 🎯 Results

## 🏆 Best Performing Models

| Model | Performance |
|---|---|
| SVM | Best overall accuracy |
| XGBoost | Strong boosting performance |
| Random Forest | Strong generalization ability |

---

## ⭐ Most Influential Features

- Sex
- Fare
- Pclass
- Age

---

# 📚 Future Improvements

Possible future enhancements:

- Cross Validation
- GridSearchCV
- Ensemble Stacking
- Deep Learning Models
- Advanced Feature Engineering

---

# 👨‍💻 Author

<div align="center">

## Marouane Elallaoui

Machine Learning & Data Science Enthusiast

</div>

---

<div align="center">

⭐ Feel free to star the repository if you found this project useful.

</div>