# Logistic-Regression-Breast-Cancer

This project demonstrates how to use Logistic Regression for binary classification using the Breast Cancer Wisconsin dataset. It includes preprocessing, model training, evaluation with key metrics, and a visualization of the sigmoid function.

## Project Overview

- Binary classification: malignant vs benign tumors
- Preprocessing: feature scaling using StandardScaler
- Model: Logistic Regression from scikit-learn
- Evaluation: confusion matrix, precision, recall, ROC-AUC
- Threshold tuning for improved control over predictions
- Sigmoid function plotted to explain probability mapping

## Dataset

- **Name:** Breast Cancer Wisconsin Diagnostic Data
- **Source:** [Kaggle - UCI ML Repository](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data)
- **Target Variable:** `diagnosis` (`M` = Malignant, `B` = Benign)

## Tools & Libraries

- Python
- Pandas, NumPy
- scikit-learn
- Matplotlib

## How to Run

1. Clone this repository or download the notebook.
2. Upload the Kaggle CSV file (`data.csv`) to your Google Colab or local environment.
3. Run the notebook to train the model and view the evaluation results and plots.

## Results

- Model trained using Logistic Regression
- ROC Curve plotted with AUC score
- Precision and recall shown at both default and tuned thresholds
- Sigmoid curve visualized to illustrate decision boundary mechanics

## Visualizations

   ### ROC Curve

   ### Sigmoid Function

## Concepts Covered

- Logistic Regression for binary classification
- Data standardization
- Classification threshold tuning
- Sigmoid activation function
- Model evaluation metrics: confusion matrix, precision, recall, ROC-AUC

