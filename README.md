# ML Healthcare Readmission Prediction

## Overview

This project was developed as part of the **Unit 25 – Machine Learning** assignment. The objective of the project is to apply machine learning techniques to predict whether a patient is likely to be readmitted to the hospital based on historical healthcare data.

Hospital readmissions are a major concern in healthcare systems because they increase operational costs and indicate potential gaps in patient care. By using machine learning algorithms, healthcare organizations can analyse patient records and identify individuals who are at higher risk of readmission.

This project follows the **HealthGuard scenario**, where predictive analytics is used to support better healthcare decision-making and improve patient outcomes.

---

## Project Objectives

The main objectives of this project are:

- Understand the fundamental concepts of machine learning
- Analyse healthcare data using Python
- Perform data preprocessing and feature preparation
- Implement machine learning classification algorithms
- Evaluate model performance using different metrics
- Identify the most effective algorithm for predicting patient readmission

---

## Dataset

The dataset used in this project contains healthcare records of diabetic patients collected from multiple hospitals.

Key characteristics of the dataset:

- **Total Records:** 101,766 patient visits  
- **Total Features:** 50 attributes  
- **Domain:** Healthcare / Hospital Data  

The dataset includes information such as:

- Patient demographics
- Medical diagnoses
- Hospital admission details
- Laboratory procedures
- Medication information
- Number of previous hospital visits

### Dataset Preview


<img width="1754" height="835" alt="dataset_preview" src="https://github.com/user-attachments/assets/9b023965-eaf9-4b85-8d83-c8f8a410e486" />


---

## Target Variable

The target variable used for prediction is:

The original dataset contains three categories:

- **NO** – Patient was not readmitted  
- **>30** – Patient was readmitted after more than 30 days  
- **<30** – Patient was readmitted within 30 days  

For machine learning classification, the target variable was converted into binary form:

- **0 → Not readmitted**
- **1 → Readmitted**

---

## Technologies Used

The project was implemented using the following tools and technologies:

- Python
- Jupyter Notebook
- Pandas – Data analysis
- NumPy – Numerical operations
- Matplotlib – Data visualization
- Seaborn – Statistical visualization
- Scikit-learn – Machine learning algorithms

---

## Machine Learning Models Implemented

Three classification algorithms were implemented and evaluated.

### Logistic Regression
A statistical machine learning algorithm used for binary classification problems. It models the probability of a particular class outcome.

### Decision Tree
A tree-based algorithm that splits the dataset into smaller subsets based on decision rules derived from the features.

### Random Forest
An ensemble learning method that combines multiple decision trees to improve predictive performance and reduce overfitting.

---

## Project Workflow

The machine learning workflow used in this project includes the following steps:

1. Data loading and dataset exploration  
2. Data cleaning and preprocessing  
3. Handling missing values  
4. Feature encoding for categorical variables  
5. Train-test data splitting  
6. Model training using multiple algorithms  
7. Model performance comparison  
8. Evaluation using classification metrics  
9. Overfitting analysis and model tuning  

---

## Model Performance

The models were evaluated using accuracy scores.

| Model | Accuracy |
|------|------|
| Logistic Regression | 61.45% |
| Decision Tree | 56.03% |
| Random Forest | 63.83% |

After model tuning:

- **Training Accuracy:** 65.9%  
- **Testing Accuracy:** 63.9%

The **Random Forest model** produced the best overall performance.

### Model Accuracy Comparison

<img width="1234" height="470" alt="model_accuracy_comparison" src="https://github.com/user-attachments/assets/64f2c273-cc88-4443-a6ab-4bc213477856" />


---

## Evaluation Metrics

To analyse the effectiveness of the machine learning models, several evaluation metrics were used:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- Feature Importance

### Confusion Matrix

<img width="1273" height="482" alt="confusion_matrix1" src="https://github.com/user-attachments/assets/8eb357fe-d6b1-46ef-878f-78f800754041" />

### Confusion Matrix Graph Image
<img width="843" height="505" alt="confusion_matrix_graph" src="https://github.com/user-attachments/assets/f1453df1-e7f6-4d02-b546-794e01feecbb" />

### ROC Curve
<img width="1186" height="615" alt="train_test_split" src="https://github.com/user-attachments/assets/c954bacf-2f26-4809-b0e6-1f479359d6a1" />

### ROC Curve Graph
<img width="830" height="609" alt="roc_curve_graph" src="https://github.com/user-attachments/assets/dce1aa5c-d85b-4119-aeab-9dd7f0b86e95" />

### Feature Importance
<img width="1407" height="538" alt="feature_importance1" src="https://github.com/user-attachments/assets/4d58a461-fce1-43a7-89cc-406eb4d77b13" />

### Feature Importance Graph
<img width="1332" height="769" alt="feature_importance_graph" src="https://github.com/user-attachments/assets/76533fbd-6a66-48c8-b098-6fe9a2fedc1d" />

## Repository Structure

```text
ML-Healthcare-Readmission-Prediction-
├── Data
│   └── diabetic_data.csv
├── Images
│   ├── dataset_preview.png
│   ├── dataset_structure.png
│   ├── missing_values_check.png
│   ├── readmitted_distribution.png
│   ├── train_test_split.png
│   ├── model_accuracy_comparison.png
│   ├── classification_report.png
│   ├── confusion_matrix.png
│   ├── roc_curve.png
│   ├── feature_importance.png
├── Notebook
│   └── healthcare_readmission_prediction.ipynb
├── Presentation
│   ├── ML_Theory_Presentation.pptx
│   └── ML_Healthcare_Presentation.pptx
├── requirements.txt
└── README.md
```

---

## Key Findings

The analysis of the dataset shows that several factors influence hospital readmission, including:

- Number of previous inpatient visits
- Number of diagnoses
- Time spent in hospital
- Number of medications prescribed

Machine learning models can help identify these patterns and support healthcare providers in managing patient care more effectively.

---

## Conclusion

This project demonstrates how machine learning techniques can be applied to healthcare data to predict patient readmissions. By analysing historical patient records and training predictive models, healthcare organizations can gain valuable insights into patient risk patterns.

Predictive analytics tools such as Random Forest models can support hospitals in identifying high-risk patients, reducing readmission rates, and improving overall healthcare service quality.

---

## Author

**Anish Kumar Thakur**

Machine Learning Project – Healthcare Readmission Prediction
