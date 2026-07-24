# Advanced Feature Engineering Techniques

## Project Overview

This project demonstrates the application of advanced feature engineering techniques to improve the performance of a machine learning classification model using the **Titanic Survival Prediction Dataset**.

Feature engineering is a crucial step in the machine learning pipeline because it transforms raw data into more informative features that help models learn complex relationships and improve predictive performance.

The project compares a baseline Random Forest Classifier with a model trained on engineered features to evaluate the impact of different feature engineering techniques.

---

# Dataset

**Dataset:** Titanic Survival Prediction

**Source:** Kaggle – Titanic: Machine Learning from Disaster

**Type:** Binary Classification

**Target Variable:** `Survived`

Main Features:

* Passenger Class (Pclass)
* Age
* Fare
* Sex
* Number of Siblings/Spouses (SibSp)
* Number of Parents/Children (Parch)
* Embarked Port

---

# Project Workflow

1. Load the dataset.
2. Perform Exploratory Data Analysis (EDA).
3. Clean and preprocess the data.
4. Train a baseline Random Forest model.
5. Apply advanced feature engineering techniques.
6. Retrain the model using engineered features.
7. Compare model performance.
8. Analyze the impact of feature engineering.

---

# Feature Engineering Techniques

The following techniques were implemented:

* Data Cleaning
* One-Hot Encoding
* Polynomial Features
* Interaction Features
* Log Transformation
* Yeo-Johnson Power Transformation

These techniques help capture non-linear relationships, reduce skewness, and improve feature representation.

---

# Machine Learning Model

**Algorithm Used:**

* Random Forest Classifier

**Evaluation Metrics:**

* Accuracy
* Precision
* Recall
* F1 Score

Performance was evaluated before and after feature engineering to measure the effectiveness of the engineered features.

---

# Project Structure

```text
README.md
requirements.txt

notebooks/
└── feature_engineering.ipynb

docs/
└── impact_report.md

data/
└── raw_dataset_info.txt
```

---

# Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

# Learning Outcomes

Through this project, I gained practical experience in:

* Exploratory Data Analysis (EDA)
* Data Cleaning
* Feature Engineering
* Polynomial Features
* Interaction Features
* Mathematical Transformations
* Machine Learning Model Training
* Model Evaluation
* Performance Comparison
* Data Visualization

---

# Future Improvements

Possible future enhancements include:

* Applying advanced feature selection techniques.
* Comparing additional machine learning algorithms.
* Hyperparameter tuning.
* Experimenting with higher-degree polynomial features.
* Applying feature engineering to larger real-world datasets.
