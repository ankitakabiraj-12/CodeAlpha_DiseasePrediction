# CodeAlpha — Disease Prediction

A machine learning-based heart disease prediction system developed using the **UCI Heart Disease Dataset**. The project implements and compares multiple classification algorithms to predict the presence or absence of heart disease, along with disease risk probability and explainable feature importance.

## 📌 Project Overview

Heart disease prediction is an important application of machine learning in healthcare. By analyzing patient medical attributes, machine learning models can identify patterns associated with the presence of heart disease.

This project develops a binary classification system using multiple machine learning algorithms and evaluates their performance using standard classification metrics.

In addition to disease prediction, the project provides:

* **Disease Risk Probability**
* **Explainable Prediction using Feature Importance**

These features help make the model predictions more informative and interpretable.

## 🎯 Objectives

The main objectives of this project are:

* Build a machine learning system for heart disease prediction.
* Perform data preprocessing and preparation.
* Analyze patient medical attributes.
* Train multiple classification algorithms.
* Compare model performance using standard evaluation metrics.
* Estimate the probability of heart disease.
* Provide explainable insights using feature importance.

## 📊 Dataset

The project uses the **UCI Heart Disease Dataset**, specifically the **Cleveland Heart Disease Dataset**.

The dataset contains medical attributes related to cardiovascular health, including:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol
* Fasting Blood Sugar
* Resting ECG
* Maximum Heart Rate
* Exercise-Induced Angina
* ST Depression
* Number of Major Vessels
* Thalassemia
* Heart Disease Target

### Target Transformation

The original dataset contains multiple target values representing different levels of heart disease.

For this project, the target variable is converted into a binary classification problem:

```text
0 → No Heart Disease
1 → Heart Disease Present
```

## 🤖 Machine Learning Models

The project implements and compares the following classification algorithms:

### 1. Logistic Regression

A linear classification algorithm used to establish a baseline for heart disease prediction.

### 2. Support Vector Machine (SVM)

A supervised learning algorithm that identifies an optimal decision boundary between different classes.

### 3. Random Forest

An ensemble learning algorithm that combines multiple decision trees to improve prediction performance and robustness.

### 4. XGBoost

A gradient boosting algorithm designed to provide strong predictive performance by sequentially building an ensemble of decision trees.

## 🔬 Key Features

### ❤️ Heart Disease Prediction

The trained machine learning models predict whether a patient is classified as having heart disease or not.

### 📈 Disease Risk Probability

The system provides a probability-based estimation associated with the predicted class, giving additional context beyond a simple binary prediction.

### 🔍 Explainable Prediction

Feature importance analysis is used to identify which patient attributes contribute most significantly to the model's predictions.

This helps improve the interpretability of the machine learning system.

## 📏 Model Evaluation

The classification models can be evaluated using standard machine learning metrics such as:

* **Accuracy**
* **Precision**
* **Recall**
* **F1-Score**
* **ROC-AUC Score**
* **Confusion Matrix**
* **ROC Curve**

These metrics provide a comprehensive view of model performance.

## 🛠️ Technologies Used

* **Python**
* **Pandas**
* **NumPy**
* **Scikit-learn**
* **XGBoost**
* **Matplotlib**
* **Seaborn**
* **Google Colab**
* **Machine Learning**

## 📁 Project Structure

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
```

## 🔄 Project Workflow

```text
UCI Heart Disease Dataset
          ↓
Data Loading
          ↓
Data Cleaning & Preprocessing
          ↓
Exploratory Data Analysis
          ↓
Feature Preparation
          ↓
Binary Target Transformation
          ↓
Train-Test Split
          ↓
Model Training
          ↓
Model Evaluation
          ↓
Model Comparison
          ↓
Risk Probability & Feature Importance
          ↓
Heart Disease Prediction
```

## ▶️ How to Run

1. Open `CodeAlpha_DiseasePrediction.ipynb` in **Google Colab** or Jupyter Notebook.
2. Make sure the dataset files are available in the `dataset` directory.
3. Run the notebook cells sequentially.
4. Perform data preprocessing and exploratory analysis.
5. Train the machine learning models.
6. Evaluate and compare model performance.
7. Generate disease predictions and risk probabilities.
8. Analyze feature importance for model interpretability.

## 💡 Learning Outcomes

Through this project, I gained practical experience in:

* Healthcare-related machine learning
* Binary classification
* Medical dataset preprocessing
* Exploratory data analysis
* Feature engineering
* Logistic Regression
* Support Vector Machine
* Random Forest
* XGBoost
* Model evaluation
* Risk probability estimation
* Feature importance analysis
* Explainable machine learning
* Data visualization

## 🚀 Future Improvements

Future versions of the project can include:

* Hyperparameter optimization
* Cross-validation
* Advanced explainability techniques such as SHAP
* Interactive patient prediction interface
* Web-based deployment using Flask or Streamlit
* Model monitoring and performance tracking
* Improved clinical interpretability

## 🎓 Project Purpose

This project was developed as part of the **CodeAlpha Machine Learning Internship** to demonstrate the practical application of machine learning techniques to a healthcare prediction problem.

## 👩‍💻 Author

**ANKITA KABIRAJ**

BCA Final-year student 

**GitHub:** `ankitakabiraj-12`

## ⚠️ Disclaimer

This project is developed for **educational and machine learning demonstration purposes only**. It is not intended to provide medical diagnosis, treatment recommendations, or replace professional medical advice.

## 📄 License

This project is intended for educational and learning purposes.
