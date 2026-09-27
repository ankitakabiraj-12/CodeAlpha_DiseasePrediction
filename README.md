# CodeAlpha_DiseasePrediction

ML-based heart disease prediction using UCI medical data with Logistic Regression, SVM, Random Forest, and XGBoost, including risk probability and explainable feature importance.

# Objective

The main objective of this project is to build and compare multiple machine learning classification models that can predict the presence or absence of heart disease using patient medical attributes.

The project also includes two additional features:

1. **Disease Risk Probability**
2. **Explainable Prediction using Feature Importance**

# Dataset

The project uses the **UCI Heart Disease Dataset**, specifically the Cleveland heart disease data.

The dataset contains medical attributes such as:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise-Induced Angina
- ST Depression
- Number of Major Vessels
- Thalassemia
- Heart Disease Target

The original target contains multiple values representing different levels of heart disease. For this project, it was converted into a binary classification:

- `0` → No Heart Disease
- `1` → Heart Disease Present

# Technologies
▪️Python
▪️Pandas
▪️NumPy
▪️Scikit-learn
▪️XGBoost
▪️Matplotlib
▪️Seaborn
▪️Google Colab

# Project Structure

```text
CodeAlpha_DiseasePrediction/
│
├── dataset/
│   ├── cleveland.data
│   ├── cleve.mod
│   ├── heart-disease.README
│   ├── heart-disease.cost
│   ├── heart-disease.delay
│   ├── heart-disease.expense
│   └── heart-disease.group
│
├── CodeAlpha_DiseasePrediction.ipynb
│
└── README.md

