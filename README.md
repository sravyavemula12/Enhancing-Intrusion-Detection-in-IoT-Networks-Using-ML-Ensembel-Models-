Intrusion Detection System using Ensemble Machine Learning
Features

Ensemble of Random Forest, Gradient Boosting, XGBoost, and LightGBM

Data balancing with SMOTE

Feature selection using Recursive Feature Elimination (RFE)

Before vs After SMOTE accuracy comparison

Confusion matrices and feature correlation heatmaps

Tech Stack

Python 3.x

Pandas, NumPy

Scikit-learn

XGBoost, LightGBM

Imbalanced-learn (SMOTE)

Matplotlib, Seaborn

How It Works

Load and preprocess dataset (encoding, scaling, missing value handling)

Apply SMOTE to balance classes

Select top features using RFE

Train individual models and combine using soft-voting ensemble

Evaluate with accuracy, classification report, confusion matrices, and heatmaps
