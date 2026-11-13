# Logistic Regression for Customer Churn Prediction

## Project Overview
This project implements Logistic Regression from scratch to predict customer churn using the Telco Customer Churn dataset.

The project explores different optimization algorithms and compares their performance in binary classification.

## Dataset
**Telco Customer Churn Dataset**

The dataset contains customer information, services, contract details, monthly charges, total charges, and churn status.

**Target Variable:**
- `0`: No Churn
- `1`: Churn

## Data Preprocessing
The following preprocessing steps were performed:
- Handling missing values.
- Removing unnecessary columns.
- Encoding categorical features.
- Separating features and target variable.
- Splitting data into training and testing sets.
- Applying feature scaling using StandardScaler.

## Logistic Regression Implementation
Logistic Regression was implemented from scratch using NumPy, including:
- Parameter Initialization
- Sigmoid Function
- Forward Propagation
- Binary Cross-Entropy Loss
- Gradient Computation
- Prediction Function

## Optimization Algorithms
The project explores the following optimization algorithms:
1. Gradient Descent (GD)
2. Stochastic Gradient Descent (SGD)
3. Mini-Batch Gradient Descent
4. RMSprop
5. Adam

SGD and Mini-Batch Gradient Descent are also implemented with and without Momentum.

## Model Evaluation
Models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Binary Cross-Entropy Loss

Training Loss curves are also used to visualize and compare model convergence.

## Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Structure

```text
Logistic-Regression-Customer-Churn/
│
├── 01_GD.ipynb
├── 02_SGD.ipynb
├── 03_Mini_Batch.ipynb
├── 04_RMSprop.ipynb
├── 05_Adam.ipynb
│
└── README.md
```

## Project Objective
To understand Logistic Regression from scratch and compare different optimization algorithms based on their training behavior and classification performance.
