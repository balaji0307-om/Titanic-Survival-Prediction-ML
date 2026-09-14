# 🚢 Titanic Survival Prediction ML

A simple Machine Learning classification project that predicts whether a Titanic passenger survived using a **Decision Tree Classifier**.

## 📌 Project Overview

The project uses passenger information such as passenger class, gender, siblings/spouses, parents/children, and embarkation port to predict the **Survived** outcome.

## 🧠 Workflow

```text
Titanic Dataset
      ↓
Data Exploration
      ↓
Data Preprocessing
      ↓
Feature Encoding
      ↓
Train-Test Split (80/20)
      ↓
Decision Tree Classifier
      ↓
GridSearchCV Tuning
      ↓
Prediction
      ↓
Accuracy + Confusion Matrix
```

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 🤖 Machine Learning Model

The project first trains a **Decision Tree Classifier** and then uses **GridSearchCV** to tune its hyperparameters.

Evaluation includes:

- Accuracy
- Confusion Matrix
- Classification Report

The tuned model is also visualized as a decision tree and its feature importance is displayed.

## 📂 Project Structure

```text
Titanic-Survival-Prediction-ML/
│
├── Dataset/
│   └── Titanic-Dataset - Titanic-Dataset.csv
├── main.py
├── requirements.txt
├── README.md
└── .gitignore
```

## 🚀 How to Run

Create and activate a virtual environment:

```bash
python -m venv venv
venv\Scripts\activate
```

Install dependencies:

```bash
python -m pip install -r requirements.txt
```

Run the project:

```bash
python main.py
```

The program displays model results and generates visualizations for the confusion matrix, decision tree, and feature importance.

## 🎯 Learning Outcomes

- Data preprocessing
- Categorical encoding
- Classification
- Decision Trees
- Train-test splitting
- Hyperparameter tuning with GridSearchCV
- Confusion matrix analysis
- Feature importance

## 👨‍💻 Author

**Bala Ji**

GitHub: https://github.com/balaji0307-om
