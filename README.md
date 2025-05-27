# Group10_Heart-Disease-Prediction
Project Overview
This project aims to build a machine learning classification model to predict whether a person has heart disease based on various medical features. The dataset used comes from Kaggle and includes parameters like age, chest pain type, cholesterol levels, and more. The model helps in early diagnosis, supporting clinical decision-making.
**Dataset**
Source: Heart Disease Dataset - Kaggle

Key Features:

Age

Sex

ChestPainType

RestingBP

Cholesterol

FastingBS

RestingECG

MaxHR

ExerciseAngina

Oldpeak

ST_Slope

HeartDisease (target variable: 0 = No, 1 = Yes)
**Tech Stack**
Python

Libraries:

pandas

numpy

seaborn

matplotlib

scikit-learn
**Project Workflow**
1. Data Exploration
Loaded dataset with pandas

Inspected with .head(), .info(), .describe()

Checked for null values and duplicates

2. Data Visualization
Distribution plots for numerical features

Count plots for categorical variables

Correlation heatmap and pairplots

3. Data Preprocessing
Label encoding and one-hot encoding for categorical features

Feature scaling using StandardScaler

Train-test split (80:20)

Class balance check (considered SMOTE if needed)

4. Model Training and Evaluation
Trained the following models:

Logistic Regression

Decision Tree

Random Forest

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

**Evaluation metrics:**

Accuracy

Precision

Recall

F1 Score

ROC Curve and AUC Score

**5. Visualization**
Confusion matrix (heatmap)

ROC curve

Feature importance (Random Forest)

**Results**
Best model: Random Forest

Top features: ChestPainType, Oldpeak, MaxHR

Best AUC Score: Achieved with Random Forest classifier
