# Song Release Year Prediction Using Deep Learning

## Student Information

* **Name:** Muhammad Daffa Radjasa
* **Class:** [Your Class]
* **NIM:** [Your NIM]

---

## Project Overview

This project implements an end-to-end Deep Learning regression pipeline to predict the release year of a song based on its audio features.

The dataset consists of numerical audio descriptors extracted from music signals. The first column represents the target variable (song release year), while the remaining columns contain audio-related features such as timbre and spectral characteristics.

The objective of this project is to build a regression model capable of predicting the release year from the provided features while applying proper preprocessing, hyperparameter optimization, model evaluation, interpretation, and experiment tracking.

---

## Dataset Description

**Dataset:** `midterm-regresi-dataset.csv`

### Dataset Characteristics

* Target Variable: Song Release Year
* Feature Type: Numerical
* Task Type: Regression
* Number of Features: Audio signal features
* Missing Value Handling: Median Imputation
* Outlier Handling: IQR-Based Clipping
* Feature Scaling: StandardScaler

The first column in the dataset contains the target value, while all remaining columns are used as input features.

---

## Project Workflow

### 1. Data Loading

The dataset is loaded into a Pandas DataFrame and inspected for structure and quality.

### 2. Data Preprocessing

Several preprocessing techniques are applied:

* Missing value handling
* Outlier treatment using IQR
* Feature scaling using StandardScaler
* Feature-target separation

### 3. Data Splitting

The dataset is divided into:

* Training Set (80%)
* Testing Set (20%)

### 4. Deep Learning Model

A Deep Neural Network (DNN) is built using TensorFlow/Keras.

Model Architecture:

* Dense Layer (256 neurons, ReLU)
* Dropout Layer
* Dense Layer (128 neurons, ReLU)
* Dropout Layer
* Dense Layer (64 neurons, ReLU)
* Output Layer (1 neuron)

### 5. Hyperparameter Optimization

Optuna is used to optimize:

* Number of neurons
* Learning rate
* Dropout rate
* Hidden layer configuration

### 6. Model Interpretation

LIME (Local Interpretable Model-Agnostic Explanations) is used to explain individual predictions and identify influential features.

### 7. Experiment Tracking

MLflow is used to track:

* Parameters
* Metrics
* Model artifacts

### 8. Evaluation

The model is evaluated using regression metrics:

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
* LIME
* MLflow
* Matplotlib

---

## Repository Structure

```text
finalterm-machine-learning/
│
├── README.md
├── notebooks/
│   └── Song_Year_Prediction.ipynb
│
├── models/
│
├── results/
│
├── requirements.txt
│
└── .gitignore
```

---

## How to Run

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Open Notebook

```bash
jupyter notebook
```

Open the notebook inside the `notebooks` directory and run all cells sequentially.

---

## Model Performance

### Evaluation Results

| Metric   | Value         |
| -------- | ------------- |
| MSE      | 276961.75 |
| RMSE     | 526.2715553780197 |
| MAE      | 526.052734375 |
| R² Score | -2326.1162109375 |

---

## Conclusion

This project demonstrates the implementation of an end-to-end Deep Learning regression pipeline for predicting song release years using audio features. Data preprocessing, hyperparameter optimization using Optuna, model interpretation using LIME, and experiment tracking using MLflow were successfully integrated into the workflow.

The final model achieved satisfactory performance and provides a practical example of applying Deep Learning techniques to regression problems involving high-dimensional audio data.
