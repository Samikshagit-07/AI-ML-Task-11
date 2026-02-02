# AI-ML-Task-11

Project Overview

This project implements a Support Vector Machine (SVM) to classify breast cancer data as either Malignant or Benign. The primary goal was to learn kernel-based classification, hyperparameter tuning using GridSearchCV, and model evaluation using ROC curves.

Dataset

Primary Source: Scikit-learn Breast Cancer dataset (load_breast_cancer()).

Features: 30 numeric attributes including radius, texture, perimeter, and area.

Labels: Malignant (0) and Benign (1)

Workflow

Data Preprocessing: Handled feature scaling using StandardScaler to normalize values for the SVM algorithm.

Model Training: * Developed a baseline model using a Linear Kernel.

Developed a secondary model using an RBF (Radial Basis Function) Kernel.

Optimization: Utilized GridSearchCV to find the optimal values for hyperparameters C and gamma.

Evaluation: Generated a confusion matrix, classification report, and ROC-AUC score to validate performance.

Deliverables Included

Notebook: Full Python implementation of the classification pipeline.

ROC Curve & AUC Report: Visual and numerical analysis of model separability.

Saved Model: A tuned model pipeline (scaler + svm) saved as a .pkl file for future reuse.
 
 Key Interview Concepts Covered

Margin: The distance between the hyperplane and support vectors.

C Parameter: Controls the trade-off between margin width and classification error.

Gamma: Defines the influence of a single training point in the RBF kernel.

Scaling: Essential for SVM to ensure distance-based calculations are not biased by feature magnitude.
