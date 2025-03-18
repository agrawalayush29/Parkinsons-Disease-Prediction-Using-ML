# Parkinson's Disease Prediction using Machine Learning

## Overview
This project is a machine learning-based approach to predict Parkinson's disease using various classification models such as Logistic Regression, XGBoost, and SVM. The dataset is preprocessed, important features are selected, and oversampling is used to balance the dataset.

## Dataset
The dataset used in this project contains various attributes related to Parkinson's disease, including voice and movement-related biomarkers.

## Features Implemented
- **Data Preprocessing:** Handling missing values, removing correlated features, and feature scaling.
- **Feature Selection:** Using SelectKBest and chi-square test to select the top 30 most relevant features.
- **Oversampling:** Applying RandomOverSampler to balance the dataset.
- **Model Training:** Implemented three classifiers:
  - Logistic Regression
  - XGBoost Classifier
  - Support Vector Machine (SVM)
- **Performance Evaluation:**
  - Confusion matrix visualization
  - Classification report
  - Accuracy metrics

## Results
The models were evaluated on a test set, and their validation accuracies were as follows:
- **Logistic Regression:** ~81.47%
- **XGBoost:** ~78.57%
- **SVM:** ~75.86%

## Visualizations
- **Class Distribution:** Pie chart showing the dataset imbalance.
- **Confusion Matrix:** Displaying model performance on predictions.

## Installation & Usage
1. Clone the repository:
   ```sh
   git clone https://github.com/<your-username>/parkinsons-disease-prediction-ml.git
   ```
2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
3. Run the script:
   ```sh
   python disease_prediction.py
   ```

## Dependencies
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- scikit-learn
- imbalanced-learn
- XGBoost

