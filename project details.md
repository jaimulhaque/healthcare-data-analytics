## 📋 Project Details

This project presents an end-to-end machine learning pipeline for predicting hospital readmission using the **Diabetes 130-US Hospitals (1999–2008)** dataset from the UCI Machine Learning Repository.

The primary objective is to analyze patient healthcare records, identify meaningful patterns, and develop a predictive model capable of determining whether a diabetic patient is likely to be readmitted after hospital discharge.

### 🔍 Project Scope

Throughout this project, the complete data science lifecycle was implemented, including:

### 📊 Data Understanding
- Explored the dataset structure and feature descriptions.
- Identified numerical and categorical variables.
- Examined missing values and target distribution.

### 🧹 Data Cleaning & Preprocessing
- Removed unnecessary and duplicated information.
- Handled missing and inconsistent values.
- Converted categorical variables into machine learning–ready formats.
- Prepared a clean dataset for further analysis.

### 📈 Exploratory Data Analysis (EDA)
Performed comprehensive exploratory analysis to understand patient characteristics and healthcare patterns.

Visualizations include:
- Readmission Distribution
- Age Distribution
- Gender Distribution
- Race Distribution
- Hospital Stay Distribution
- Correlation Matrix
- Summary Statistics

### ⚙️ Feature Engineering
Several new features were created to improve model performance, including:

- Numerical Age Conversion
- Total Hospital Visits
- Total Procedures
- Medication Intensity
- Hospital Stay Category
- Primary Diagnosis Availability
- One-Hot Encoding for categorical variables

### 🤖 Machine Learning Modeling
Multiple classification algorithms were developed and compared:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Each model was evaluated using identical training and testing datasets to ensure a fair comparison.

### 🎯 Hyperparameter Optimization
The Random Forest model was further optimized using **GridSearchCV** with **5-fold Cross Validation**.

The optimization process searched for the best combination of:
- Number of Trees
- Maximum Tree Depth
- Minimum Samples Split
- Minimum Samples Leaf

### 📊 Model Evaluation
The final optimized model was evaluated using multiple performance metrics, including:

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC Score
- Confusion Matrix
- Classification Report
- Feature Importance Analysis

### 💡 Project Outcome
This project demonstrates a complete healthcare data analytics workflow, from raw clinical data to an optimized machine learning model. It highlights practical experience in data preprocessing, feature engineering, predictive modeling, model optimization, and performance evaluation using Python and Scikit-learn.
