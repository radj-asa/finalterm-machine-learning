# Machine Learning Projects Repository

## Student Information

| Information | Details                |
| ----------- | ---------------------- |
| Name        | Muhammad Daffa Radjasa |
| NIM         | 1103220018             |
| Program     | Computer Engineering   |
| University  | Telkom University      |
| Course      | Machine Learning       |

---

## Repository Overview

This repository contains machine learning projects developed as part of coursework and practical assignments. The projects cover both classification and regression tasks using modern machine learning and deep learning approaches.

The repository demonstrates the complete machine learning workflow, including:

* Data preprocessing
* Missing value handling
* Outlier treatment
* Feature engineering
* Feature scaling
* Class imbalance handling
* Deep Learning model development
* Hyperparameter optimization using Optuna
* Experiment tracking using MLflow
* Model evaluation and interpretation

---

## Projects Included

### 1. Fraud Detection using Deep Learning (Classification)

#### Objective

Predict whether a transaction is fraudulent (`isFraud = 1`) or legitimate (`isFraud = 0`).

#### Dataset

* IEEE-CIS Fraud Detection Dataset
* Transaction-based financial data
* Highly imbalanced binary classification problem

#### Techniques Used

* Missing value handling
* Label Encoding
* Standard Scaling
* SMOTE Oversampling
* Deep Neural Network (TensorFlow/Keras)
* Hyperparameter Optimization (Optuna)
* MLflow Tracking

#### Evaluation Metrics

* Accuracy
* Precision
* Recall
* F1-Score
* ROC-AUC

---

### 2. Song Release Year Prediction (Regression)

#### Objective

Predict the release year of a song using audio-related numerical features.

#### Dataset

* Audio Feature Dataset
* Numerical feature-based regression problem

#### Techniques Used

* Missing value handling
* Outlier treatment using IQR
* Feature Scaling
* Deep Neural Network (TensorFlow/Keras)
* Hyperparameter Optimization (Optuna)
* LIME Explainability
* MLflow Tracking

#### Evaluation Metrics

* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)
* Mean Absolute Error (MAE)
* R² Score

---

## Technologies Used

* Python
* Google Colab
* Pandas
* NumPy
* Scikit-Learn
* TensorFlow / Keras
* Optuna
* MLflow
* LIME
* Matplotlib
* Seaborn

---

## Repository Structure

```text
MachineLearning/
│
├── README.md
│
├── Fraud_Detection/
│   ├── notebook.ipynb
│   └── results/
│
├── Song_Year_Prediction/
│   ├── notebook.ipynb
│   └── results/
│
├── requirements.txt
│
└── .gitignore
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/radj-asa/finalterm-machine-learning.git
```

Move into the project directory:

```bash
cd finalterm-machine-learning
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Learning Outcomes

Through these projects, the following machine learning concepts were applied:

* Supervised Learning
* Classification
* Regression
* Deep Learning
* Data Preprocessing
* Hyperparameter Optimization
* Model Explainability
* Experiment Tracking
* Performance Evaluation

---

## Author

**Muhammad Daffa Radjasa**
**NIM: 1103220018**
Computer Engineering — Telkom University

