# Machine Learning Classification of Hematological Data
 
## Overview
 
This project investigates the prediction of PCR test outcomes using hematological and biochemical biomarkers. The dataset contains 2,598 patient records with 38 numerical features and a binary target variable representing PCR test results. 

 
The aim of the project was to apply machine learning and mathematical modelling techniques to classify PCR outcomes and compare the performance of different algorithms.
 
## Project Objectives
 
- Explore and preprocess medical data
- Investigate feature relationships using linear algebra techniques
- Apply dimensionality reduction using Principal Component Analysis (PCA)
- Implement machine learning classification algorithms
- Evaluate model performance on imbalanced data
 
## Methods
 
The project included:
 
- Data cleaning and preprocessing
- Missing value handling
- Feature standardisation
- Covariance matrix analysis
- Principal Component Analysis (PCA)
- Logistic Regression (implemented from scratch)
- K-Nearest Neighbours (implemented from scratch)
- Support Vector Machine (SVM) modelling 【1-43d450】
 
## Dataset
 
- 2,598 patient records
- 38 biomarker features
- Binary PCR outcome target variable
- Significant class imbalance (~90% negative, ~10% positive) 
 
## Key Results
 
- Logistic Regression and SVM achieved the strongest classification performance.
- PCA demonstrated that approximately 15-18 principal components explained around 90% of dataset variance.
- Class imbalance was addressed through weighted classification techniques.
- Performance was evaluated using Accuracy, F1 Score, and ROC-AUC metrics. 
 
## Visualisations
 
### PCA Projection

<img width="488" height="349" alt="fig4" src="https://github.com/user-attachments/assets/160902c0-d7da-4ea3-adbe-c9f100bdea7f" />
 
### ROC Curve Comparison
<img width="428" height="355" alt="fig7" src="https://github.com/user-attachments/assets/4c69a12b-38b8-4c1b-95e9-00a2c7d793d3" />
 
 
## Technologies Used
 
- Python
- NumPy
- Scikit-learn
- Pandas
- Matplotlib
- Machine Learning
- Statistical Analysis
