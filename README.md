# Titanic Survivor Prediction using Logistic Regression

## Project Overview

This project predicts whether a passenger survived the Titanic disaster using Machine Learning. The model is trained on the Titanic dataset using Logistic Regression and evaluates passenger survival based on features such as passenger class, gender, age, fare, and family information.

---

## Objective

To build a classification model that predicts whether a passenger survived the Titanic disaster.

---

## Problem Type

Classification

---

## Dataset

- Dataset: Titanic Dataset
- Source: Seaborn (`sns.load_dataset("titanic")`)
- Number of Records: 891
- Target Variable: `survived`

---

## Features Used

- Passenger Class (pclass)
- Sex
- Age
- Number of Siblings/Spouses (sibsp)
- Number of Parents/Children (parch)
- Fare
- Port of Embarkation (embarked)

Target:
- survived

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Machine Learning Workflow

### 1. Problem Definition
Predict whether a passenger survived the Titanic disaster.

### 2. Data Collection
Load the Titanic dataset directly using Seaborn.

### 3. Data Preprocessing

- Handle missing values
- Encode categorical variables
- Select important features

### 4. Exploratory Data Analysis (EDA)

- Survival count
- Survival by gender
- Passenger class distribution
- Age distribution

### 5. Feature Engineering

- Label Encoding
- Feature selection

### 6. Train-Test Split

- 80% Training Data
- 20% Testing Data

### 7. Feature Scaling

StandardScaler is used to normalize numerical features.

### 8. Model Selection

Logistic Regression

### 9. Model Training

Train the Logistic Regression classifier using the training dataset.

### 10. Model Evaluation

Evaluation metrics:

- Accuracy
- Precision
- Recall
- Confusion Matrix
- Classification Report

### 11. Prediction

Predict whether a new passenger would survive.

---

## Project Structure

```
Titanic_Survivor_Prediction/
│
├── Titanic_Survivor_Prediction.ipynb
├── README.md
└── titanic_model.pkl (optional)
```

---

## Libraries Required

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## Results

The Logistic Regression model successfully predicts passenger survival using selected features.

Typical evaluation metrics include:

- Accuracy
- Precision
- Recall

(The exact values may vary depending on the train-test split.)

---

## Future Improvements

- Random Forest Classifier
- Decision Tree Classifier
- Hyperparameter tuning using GridSearchCV
- Feature engineering
- Deploy using Streamlit or Flask

---

## Conclusion

This project demonstrates a complete Machine Learning classification workflow using the Titanic dataset. It covers data preprocessing, exploratory data analysis, feature engineering, model training, evaluation, and prediction using Logistic Regression.
