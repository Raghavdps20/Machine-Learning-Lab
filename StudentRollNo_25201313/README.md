# Titanic Survival Prediction – Machine Learning Lab

## Student Information
- **Roll Number:** 25201313  
- **Subject:** Machine Learning Lab  
- **Dataset:** Titanic – Kaggle  

## Project Description
This project implements supervised machine learning models to predict whether a
passenger survived the Titanic disaster. The dataset contains passenger details
such as class, sex, age, and fare, which are used to train and evaluate models.

## Folder Structure
StudentRollNo_25201313/
│
├── easy.ipynb
├── moderate.ipynb
├── hard.ipynb
├── README.md
└── requirements.txt

## Tasks Implemented
- **Easy:** Logistic Regression using limited features (Pclass, Sex, Age)
- **Moderate:** Support Vector Machine (Linear Kernel) with feature scaling and
  hyperparameter tuning
- **Hard:** Comparison of KNN and SVM models based on ROC-AUC and
  bias–variance tradeoff

## Model Selection Reasoning
Logistic Regression was chosen for the easy task due to its simplicity and
interpretability. For the moderate task, a linear SVM was used because it handles
feature scaling and regularization effectively. In the hard task, KNN and SVM
were compared; KNN exhibited higher variance and sensitivity to noise, while SVM
provided better generalization and a higher ROC-AUC score. Therefore, SVM was
selected as the final model.

## Evaluation Metrics
- **Easy:** Accuracy, F1-Score  
- **Moderate:** ROC-AUC  
- **Hard:** ROC-AUC (KNN vs SVM comparison)
