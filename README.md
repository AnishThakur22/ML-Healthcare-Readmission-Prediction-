# ML Healthcare Readmission Prediction

## Overview
This project was developed for the Unit 25: Machine Learning assignment. The main objective of the project is to apply machine learning techniques to predict whether a patient is likely to be readmitted to the hospital based on historical healthcare data.

The project is based on the HealthGuard scenario, where machine learning is used to improve patient care, reduce readmission rates, and support healthcare decision-making.

## Objectives
- Analyse machine learning concepts and algorithms
- Prepare and preprocess healthcare data
- Develop machine learning models for readmission prediction
- Evaluate model performance using multiple metrics
- Recommend the most suitable model for healthcare use

## Dataset
The project uses the diabetic patient dataset containing 101,766 records and 50 attributes. The dataset includes patient demographic details, medical history, hospital admission information, and treatment-related features.

Target variable:
- `readmitted`

## Tools and Technologies
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Machine Learning Models Used
- Logistic Regression
- Decision Tree
- Random Forest

## Project Workflow
1. Dataset loading and exploration
2. Data cleaning and preprocessing
3. Feature engineering and encoding
4. Train-test split
5. Model implementation
6. Model evaluation
7. Overfitting analysis
8. Final recommendation

## Results
Model accuracy comparison:
- Logistic Regression: 61.45%
- Decision Tree: 56.03%
- Random Forest: 63.83%

After model tuning:
- Training Accuracy: 65.9%
- Testing Accuracy: 63.9%

The Random Forest model performed best and provided the most balanced performance.

## Evaluation Metrics
The models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve
- Feature Importance

## Repository Structure
- `data/` contains the dataset
- `notebook/` contains the Jupyter Notebook
- `images/` contains screenshots and graphs
- `report/` contains the assignment report
- `presentation/` contains both presentation files

## Conclusion
This project shows that machine learning can support healthcare analytics by identifying patients who are at higher risk of hospital readmission. Predictive models like Random Forest can help healthcare organizations improve decision-making and patient care.

## Author
Anish Kumar Thakur
