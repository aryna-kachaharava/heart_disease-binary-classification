# Heart Disease Classification

## Project Overview

This project focuses on predicting the presence of heart disease using machine learning classification models.

The workflow includes:

* Exploratory Data Analysis (EDA)
* Data preprocessing
* Feature engineering
* Model training and evaluation
* Cross-validation
* Feature importance analysis

The goal is to identify patients at risk of heart disease based on clinical and demographic features.

---

## Dataset

The dataset contains medical information about patients, including:

* Age
* Sex
* Chest pain type
* Resting blood pressure
* Cholesterol level
* Maximum heart rate
* Exercise-induced angina
* Other clinical measurements

Target variable:

* **0** – No Heart Disease
* **1** – Heart Disease

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

### 1. Exploratory Data Analysis

* Distribution analysis
* Correlation analysis
* Target variable exploration
* Feature visualization

### 2. Data Preprocessing

* Missing value handling
* Feature transformation
* Train-test split
* Pipeline implementation

### 3. Model Training

The following classification models were evaluated:

* Logistic Regression
* Random Forest Classifier
* Other baseline models

### 4. Model Evaluation

Evaluation metrics:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC

Cross-validation was used to assess model stability.

---

## Results

The best-performing model achieved strong classification performance in detecting heart disease cases.

Special attention was given to Recall, since missing a patient with heart disease (False Negative) is more critical than generating a False Positive prediction.

---

## Feature Importance

Feature importance analysis was performed to identify the variables that contributed most to model predictions.

Key influential features included:

* Age
* Chest pain characteristics
* Maximum heart rate
* Other clinical indicators

---

## Key Takeaways

* Machine learning models can effectively identify heart disease risk.
* Proper preprocessing and validation improve model reliability.
* Feature importance helps interpret model decisions.

---

## Repository Structure

```text
heart-disease-classification/
│
├── heart.csv
├── heart_disease.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

---

## Author

Aryna Kachaharava

Aspiring Machine Learning Engineer
