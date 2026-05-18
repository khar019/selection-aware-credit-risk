# Selection-Aware Credit Risk Modeling

Advanced machine learning project focused on reject inference, survival analysis, calibration, and fairness diagnostics using the Home Credit Default Risk dataset.

## Overview

Traditional credit risk models are trained only on approved applicants, creating selection bias because rejected applicants never generate repayment outcomes.

This project investigates how selection bias impacts:
- probability calibration
- model ranking performance
- survival analysis
- fairness diagnostics

We built a synthetic approval filter and evaluated multiple correction methods under population shift.

## Methods

### Baseline Models
- Logistic Regression
- XGBoost

### Reject Inference
- Parcelling
- EM Reclassification
- Inverse Probability Weighting (IPW)

### Survival Analysis
- Cox Proportional Hazards
- DeepHitSingle

## Key Findings

- Selection bias hurts calibration more than ranking
- Simpler models generalized more robustly under population shift
- Survival analysis exposed temporal bias hidden by binary classification
- Reject inference improvements were modest under observable selection

## Tech Stack

- Python
- Pandas
- Scikit-learn
- XGBoost
- Lifelines
- Scikit-survival
- Google Colab

## Contributors

- Harelle Keli
- Michael Beyer
- Aryan Sanan
- Lacy Dove

## Academic Context

Final project for Advanced Machine Learning  
McCombs School of Business — UT Austin
