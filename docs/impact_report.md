# Feature Engineering Impact Report

# 1. Introduction

This report summarizes the impact of advanced feature engineering techniques on the performance of a machine learning classification model using the Titanic Survival Prediction dataset.

The objective was to investigate whether transforming and engineering features could improve the predictive capability of a Random Forest Classifier compared to a baseline model.

---

# 2. Dataset

**Dataset:** Titanic Survival Prediction

**Source:** Kaggle – Titanic: Machine Learning from Disaster

**Problem Type:** Binary Classification

**Target Variable:** Survived

The dataset contains passenger information such as age, fare, passenger class, family information, and gender.

---

# 3. Baseline Model

A Random Forest Classifier was trained using the cleaned dataset before applying any advanced feature engineering techniques.

The baseline model established the initial benchmark using the following evaluation metrics:

* Accuracy
* Precision
* Recall
* F1 Score

These metrics served as the reference point for evaluating the effectiveness of engineered features.

---

# 4. Feature Engineering Techniques Applied

## Polynomial Features

Polynomial Features generated higher-order numerical features and interaction terms from existing variables.

Examples:

* Age²
* Fare²
* Age × Fare

These features helped capture non-linear relationships within the dataset.

---

## Interaction Features

Several meaningful interaction variables were manually created, including:

* Age × Fare
* Pclass × Fare
* Family Size
* SibSp × Parch

These interaction features represented relationships between variables that were not directly available in the original dataset.

---

## Log Transformation

A logarithmic transformation was applied to the Fare feature to reduce positive skewness.

Benefits:

* Reduced influence of extreme values.
* Produced a more balanced distribution.
* Improved numerical stability.

---

## Yeo-Johnson Transformation

The Yeo-Johnson Power Transformation further normalized the Fare feature.

Unlike the Box-Cox transformation, Yeo-Johnson can handle zero values, making it suitable for the Titanic dataset.

---

# 5. Performance Comparison

The engineered dataset was used to train the Random Forest Classifier again.

The model performance was compared using:

* Accuracy
* Precision
* Recall
* F1 Score

The comparison demonstrated the overall impact of feature engineering on predictive performance.

---

# 6. Impact of Feature Engineering

The applied feature engineering techniques produced several benefits:

* Captured hidden non-linear relationships.
* Improved feature representation.
* Reduced skewness in numerical variables.
* Created meaningful interaction variables.
* Increased the information available to the machine learning model.

Although the magnitude of improvement depends on the dataset and algorithm, feature engineering enhanced the model's ability to learn useful patterns from the data.

---

# 7. Challenges

Some challenges encountered during this project included:

* Selecting meaningful interaction features.
* Preventing excessive feature generation.
* Managing skewed numerical distributions.
* Maintaining model interpretability while increasing feature complexity.

These challenges were addressed by carefully selecting engineered features and applying appropriate mathematical transformations.

---

# 8. Conclusion

Advanced feature engineering significantly enhanced the dataset by generating informative features and transforming numerical variables into more suitable representations.

The project demonstrated that feature engineering is an essential stage of the machine learning pipeline because well-designed features often contribute more to model performance than simply changing algorithms.

Overall, this project strengthened practical skills in data preprocessing, feature engineering, machine learning, and performance evaluation.
