# 🏥 Healthcare Data Analytics & Machine Learning

An end-to-end Machine Learning project for predicting hospital readmission using healthcare data.

This project demonstrates the complete data science workflow, including data preprocessing, exploratory data analysis, feature engineering, machine learning model development, hyperparameter tuning, and final model evaluation.

---
# 🏥 Healthcare Data Analytics & Machine Learning

[Badges]
---
![Python](https://img.shields.io/badge/Python-3.12-blue)

![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange)

![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-green)

![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

![License](https://img.shields.io/badge/License-MIT-red)


## 📖 Project Overview

Hospital readmission is a significant challenge in healthcare systems, affecting both patient outcomes and medical costs.

This project develops a machine learning pipeline to predict whether a diabetic patient is likely to be readmitted after hospital discharge.

The workflow covers every stage of a real-world data science project, from raw data preprocessing to model optimization and final evaluation.

## 🎯 Objectives
- Understand the healthcare dataset
- Clean and preprocess raw data
- Perform exploratory data analysis
- Engineer meaningful features
- Train multiple machine learning models
- Compare model performance
- Optimize the best model using Grid Search
- Evaluate the final model using multiple performance metrics

## 📂 Dataset Information

This project uses the **Diabetes 130-US Hospitals for Years 1999–2008** dataset from the UCI Machine Learning Repository.

The dataset contains over **100,000** hospital admission records collected from **130 US hospitals** over a ten-year period. It includes demographic information, laboratory procedures, medications, diagnoses, hospital stay details, and patient readmission status.

### Dataset Statistics

- **Total Records:** 101,766
- **Hospitals:** 130
- **Time Period:** 1999–2008
- **Target Variable:** Readmission
- **Prediction Type:** Binary Classification

### Target Classes

- Readmitted (<30 days)
- Not Readmitted (<30 days or No Readmission)


## 🛠️ Technologies Used

The project was developed using the following tools and libraries:

| Technology | Purpose |
|------------|---------|
| Python | Programming Language |
| Pandas | Data Manipulation |
| NumPy | Numerical Computing |
| Matplotlib | Data Visualization |
| Seaborn | Statistical Visualization |
| Scikit-learn | Machine Learning |
| Jupyter Notebook | Development Environment |
| Git & GitHub | Version Control |
## 📁 Project Structure

```text
Healthcare-Data-Analytics/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_Data_Understanding.ipynb
│   ├── 02_Data_Cleaning.ipynb
│   ├── 03_Exploratory_Data_Analysis.ipynb
│   ├── 04_Feature_Engineering.ipynb
│   ├── 05_Machine_Learning_Modeling.ipynb
│   ├── 06_Model_Comparison.ipynb
│   ├── 07_Hyperparameter_Tuning.ipynb
│   └── 08_Final_Model_Evaluation.ipynb
│
├── images/
├── reports/
├── README.md
├── requirements.txt
└── LICENSE
```
## 🔄 Project Workflow

The project follows a complete end-to-end machine learning workflow.

1. Data Understanding
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Preparation
6. Baseline Model Development
7. Model Comparison
8. Hyperparameter Tuning
9. Final Model Evaluation
10. Performance Analysis

## 📊 Exploratory Data Analysis

Several exploratory analyses were conducted to better understand the dataset.

The analysis includes:

- Patient Readmission Distribution
- Age Distribution
- Gender Distribution
- Race Distribution
- Length of Hospital Stay
- Correlation Matrix
- Summary Statistics

These analyses helped identify important trends and supported feature engineering decisions.

## ⚙️ Feature Engineering

Several new features were created to improve model performance.

Engineered features include:

- Age Conversion
- Total Hospital Visits
- Total Procedures
- Medication Intensity
- Hospital Stay Category
- Primary Diagnosis Availability
- One-Hot Encoded Categorical Variables

Feature engineering improved the quality of the input data for machine learning models.

---

## 🤖 Machine Learning Models

Multiple machine learning algorithms were trained and evaluated to identify the best-performing model for predicting hospital readmission.

The following models were implemented:

- Logistic Regression (Baseline Model)
- Decision Tree Classifier
- Random Forest Classifier

The Random Forest model achieved the best overall performance and was selected as the final predictive model.

---

## 🎯 Hyperparameter Tuning

To improve the predictive performance of the Random Forest model, GridSearchCV with 5-fold cross-validation was applied.

### Hyperparameter Grid

| Parameter | Values |
|-----------|---------|
| n_estimators | 100, 200 |
| max_depth | 10, 20, None |
| min_samples_split | 2, 5 |
| min_samples_leaf | 1, 2 |

### Best Parameters

| Parameter | Value |
|-----------|-------|
| n_estimators | 200 |
| max_depth | 20 |
| min_samples_split | 2 |
| min_samples_leaf | 2 |

The tuned Random Forest model achieved the highest cross-validation performance and was selected as the final model.


## 📈 Final Results

The final model was evaluated using multiple classification metrics.

The evaluation includes:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score

Performance reports, feature importance analysis, confusion matrix, and ROC curve are available in the `reports/` and `images/` directories.

---
## 📷 Visualizations

The project includes several visualizations to better understand the dataset and evaluate model performance.

### Exploratory Data Analysis

- Readmission Distribution
- Age Distribution
- Gender Distribution
- Race Distribution
- Time in Hospital Distribution
- Correlation Matrix

### Model Evaluation

- Confusion Matrix
- ROC Curve
- Feature Importance

All generated figures are stored in the **images/** directory.

---
## 🚀 Installation

Clone the repository:

```bash
git clone https://github.com/jaimulhaque/Healthcare-Data-Analytics.git
```

Move into the project directory:

```bash
cd Healthcare-Data-Analytics
```

Install the required packages:

```bash
pip install -r requirements.txt
```

## ▶️ How to Run

Run the notebooks in the following order:

1. 01_Data_Understanding.ipynb
2. 02_Data_Cleaning.ipynb
3. 03_Exploratory_Data_Analysis.ipynb
4. 04_Feature_Engineering.ipynb
5. 05_Machine_Learning_Modeling.ipynb
6. 06_Model_Comparison.ipynb
7. 07_Hyperparameter_Tuning.ipynb
8. 08_Final_Model_Evaluation.ipynb

---
---
## 📌 Future Work

Possible future improvements include:

- Implement XGBoost, LightGBM, and CatBoost models.
- Address class imbalance using SMOTE or class weighting.
- Develop a Streamlit web application for real-time predictions.
- Deploy the trained model to a cloud platform.
- Explore deep learning techniques for healthcare prediction tasks.

## 👨‍💻 Author

**Jaimul Haque**

Computer Science & Engineering (CSE)

GitHub: https://github.com/jaimulhaque

This project was developed as part of a machine learning portfolio to demonstrate practical skills in healthcare data analytics, data preprocessing, feature engineering, model development, hyperparameter tuning, and model evaluation.

---