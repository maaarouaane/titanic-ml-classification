<div align="center">

# 🚢 Titanic Survival Prediction using Machine Learning

*Predicting who survives — one algorithm at a time.*

<br/>

![Python](https://img.shields.io/badge/Python-3.10+-blue?style=for-the-badge&logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikitlearn)
![XGBoost](https://img.shields.io/badge/XGBoost-Boosting-green?style=for-the-badge)
![Status](https://img.shields.io/badge/Project-Completed-success?style=for-the-badge)

</div>

---

## 📌 Project Overview

This project focuses on predicting passenger survival on the Titanic using multiple Machine Learning classification algorithms.

The workflow covers a complete end-to-end Machine Learning pipeline including:

- Data preprocessing
- Feature engineering
- Feature selection
- Model training
- Hyperparameter tuning
- Overfitting / underfitting analysis
- Model comparison
- Data visualization

> Built using the famous **Titanic - Machine Learning from Disaster** dataset from Kaggle.

---

## 📂 Dataset

🔗 **Source:** [https://www.kaggle.com/competitions/titanic](https://www.kaggle.com/competitions/titanic)

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

**Target variable:**

```python
Survived   # 1 → Survived  |  0 → Did not survive
```

---

## ⚙️ Machine Learning Workflow

### 1️⃣ Data Cleaning
- Missing value handling
- Cabin column removal
- Age imputation
- Encoding categorical variables

### 2️⃣ Feature Engineering

New features were created such as:

```python
FamilySize
IsAlone
```

### 3️⃣ Feature Selection

Feature importance analysis was performed using:
- **SelectKBest**
- **Chi-Square Test**

Final selected features:

```python
['Pclass', 'Sex', 'Age', 'Parch', 'Fare', 'IsAlone']
```

---

## 🤖 Models Implemented

| Model | Type |
|---|---|
| Logistic Regression | Linear Model |
| Decision Tree | Tree-Based |
| Random Forest | Ensemble Learning |
| Support Vector Machine (SVM) | Margin-Based |
| K-Nearest Neighbors (KNN) | Distance-Based |
| XGBoost | Gradient Boosting |

---

## 📊 Model Evaluation

The models were evaluated using:

| Metric | Purpose |
|---|---|
| Accuracy Score | Overall performance |
| Confusion Matrix | Error breakdown |
| Classification Report | Precision, Recall, F1 |
| Feature Importance | Key predictors |
| Learning Curves | Generalization check |
| Overfitting / Underfitting Analysis | Bias-variance diagnosis |

---

## 📈 Visualizations

### 🔹 Model Comparison
![Model Comparison](images/model_comparison.png)

### 🔹 Decision Tree Visualization
![Decision Tree](images/decision_tree.png)

### 🔹 KNN Accuracy Curve
![KNN Curve](images/knn_accuracy_curve.png)

### 🔹 XGBoost Feature Importance
![XGBoost Importance](images/xgboost_importance.png)

---

## 🧠 Key Machine Learning Concepts Explored

| Concept | Description |
|---|---|
| Classification Algorithms | Core prediction methods |
| Bias vs Variance | Generalization trade-off |
| Overfitting & Underfitting | Model health analysis |
| Hyperparameter Tuning | Optimizing model performance |
| Ensemble Learning | Combining weak learners |
| Boosting | Sequential error correction |
| Feature Importance | Understanding key predictors |
| Model Generalization | Performance on unseen data |

---

## 🛠️ Technologies Used

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

## 📁 Project Structure

```bash
titanic-ml-classification/
│
├── data/                          # Raw and processed datasets
├── images/                        # Visualization outputs
├── notebooks/
│   └── titanic_classification.ipynb   # Main notebook
│
├── README.md                      # Project documentation
├── requirements.txt               # Dependencies
└── .gitignore
```

---

## 🚀 Installation & Usage

**1 — Clone the repository:**
```bash
git clone https://github.com/your-username/titanic-ml-classification.git
```

**2 — Install dependencies:**
```bash
pip install -r requirements.txt
```

**3 — Launch Jupyter Notebook:**
```bash
jupyter notebook
```

---

## 🎯 Results

### 🏆 Best Performing Models

> ✅ **Random Forest** — Best generalization across test data  
> ✅ **XGBoost** — Highest accuracy with gradient boosting

### ⭐ Most Influential Features

```
1. Sex        ████████████████████
2. Fare       ███████████████
3. Pclass     ████████████
4. Age        █████████
```

---

## 📚 Future Improvements

Possible future enhancements:

- [ ] Cross Validation
- [ ] GridSearchCV
- [ ] Ensemble Stacking
- [ ] Deep Learning Models
- [ ] Advanced Feature Engineering

---

## 👨‍💻 Author

<div align="center">

**Marouane Elallaoui**  
*Machine Learning & Data Science Enthusiast*

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/your-username)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/your-profile)
[![Kaggle](https://img.shields.io/badge/Kaggle-20BEFF?style=for-the-badge&logo=kaggle&logoColor=white)](https://kaggle.com/your-profile)

</div>

---

<div align="center">

*Feel free to ⭐ star the repo, 🍴 fork the project, or share your feedback 🚀*

</div>