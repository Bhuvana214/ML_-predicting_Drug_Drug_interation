# ML_-predicting_Drug_Drug_interation
Overview

This project applies machine learning (ML) approaches to drug discovery, focusing on predicting drug–drug interactions (DDIs) in the context of rheumatoid arthritis (RA). The workflow integrates pharmacological descriptors, ADMET properties, and network features to predict solubility (log S) and interaction risks, providing a foundation for precision medicine.

Objectives

Preprocess and prepare a dataset of RA drug properties.

Train baseline and advanced ML models to predict solubility (log S) and DDI likelihood.

Compare model performance using metrics and visualisations.

Demonstrate interpretability of features relevant to RA drug combinations.

Dataset

File: RA_drugs_solubility_dataset.csv

Contains physicochemical descriptors, ADMET properties, and drug network information.

Target Variable: Log solubility (LogS) and derived interaction scores.

Methods

Data Preparation

Feature-target separation (X and y).

Handling missing values with imputation.

Splitting into training and test sets.

Models Implemented

Linear Regression – baseline model for interpretability.

Random Forest Classifier – ensemble method for nonlinear relationships.

XGBoost – gradient boosting for improved accuracy and robustness.

Evaluation Metrics

R² and Mean Squared Error (MSE).

ROC curves and confusion matrices.

Feature importance analysis.

Visualisations

Predicted vs. actual values (LogS).

Cross-validation performance graphs.

PCA clustering for feature space exploration.

XGBoost performance plots.

Key Insights

Linear regression provides interpretable coefficients that highlight risk-driving features such as solubility, Lipinski’s violations, and hub connectivity.

Random Forest and XGBoost outperform linear regression in capturing nonlinear relationships.

Feature importance analysis aligns with pharmacological principles, supporting clinical interpretability.

Future Directions

Incorporation of patient-specific genomic and clinical data for personalised predictions.

Extension of models to other autoimmune diseases.

Integration of multi-omics datasets for deeper mechanistic insights.

Development of a clinical decision support tool for real-time healthcare use.
