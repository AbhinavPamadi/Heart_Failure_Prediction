# Heart_Failure_Prediction

A project to predict the likelihood of heart failure in patients using clinical records and supervised machine learning models.

## Project Overview

This project analyzes a heart failure dataset containing clinical features of patients to build predictive models that determine the risk of death. It includes data preprocessing, exploratory data analysis, feature selection, model training, evaluation, and insights generation.

## Dataset

- **File**: `heart_failure_clinical_records_dataset.csv`
- **Rows**: 299
- **Columns**: 13 features + 1 target variable (`DEATH_EVENT`)

### Key Features

- **age**: Age of the patient (years)
- **anaemia**: Decrease of red blood cells (boolean)
- **creatinine_phosphokinase**: Level of CPK enzyme in the blood
- **diabetes**: Whether the patient has diabetes (boolean)
- **ejection_fraction**: Percentage of blood leaving the heart at each contraction
- **high_blood_pressure**: Whether the patient has hypertension (boolean)
- **platelets**: Platelet count in blood
- **serum_creatinine**: Level of creatinine in the blood
- **serum_sodium**: Level of sodium in the blood
- **sex**: Gender (1 = male, 0 = female)
- **smoking**: Whether the patient smokes (boolean)
- **time**: Follow-up period (days)
- **DEATH_EVENT**: Whether the patient died during the follow-up period

## Tech Stack

- Python
- Jupyter Notebook
- pandas, NumPy
- matplotlib, seaborn
- scikit-learn

## Workflow

1. **Data Preprocessing**
   - Handling missing values (if any)
   - Encoding categorical variables
   - Feature scaling

2. **Exploratory Data Analysis**
   - Visualization of feature distributions
   - Correlation analysis

3. **Modeling**
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)
   - K-Nearest Neighbors (KNN)

4. **Evaluation**
   - Confusion Matrix
   - Accuracy, Precision, Recall, F1-score
   - ROC-AUC curve

5. **Feature Importance Analysis**

## Objective

The goal is to build a reliable and interpretable machine learning model that can assist medical professionals in assessing the risk of heart failure based on patient health metrics.

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/AbhinavPamadi/Heart_Failure_Prediction.git
   cd Heart_Failure_Prediction
   ```
2. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the notebook:
   ```bash
   jupyter notebook main.ipynb
   ```
4.Run all cells to explore the data, train models, and evaluate performance.


