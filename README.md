# Cancer Detection

## Problem Statement
Detect whether a breast tumor is malignant or 
benign based on cell characteristics using 
Machine Learning.

## Dataset
- Source: Scikit-learn built-in dataset (load_breast_cancer)
- Size: 569 rows, 30 features
- Target: 0 = Malignant, 1 = Benign
- No external dataset needed

## Algorithm Used
Support Vector Machine (SVM) with RBF Kernel

## Results
- Accuracy: 98.2%
- False Negative: 0 (never missed a cancer case!)
- Evaluated using Confusion Matrix and Classification Report

## Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Steps Performed
1. Data Loading (sklearn built-in)
2. Data Exploration
3. Feature Scaling (StandardScaler)
4. Train Test Split (80/20)
5. Model Training (SVM - RBF Kernel)
6. Model Evaluation (Accuracy, Confusion Matrix)
7. Visualization (Confusion Matrix Heatmap)

## Key Findings
- SVM achieved 98.2% accuracy on cancer detection
- Zero False Negatives — never wrongly classified cancer patient as healthy
- Feature scaling was critical for SVM performance
- RBF kernel handled complex decision boundary effectively
