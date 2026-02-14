# Trust-STROKE: Trustworthy Stroke Risk Prediction with Calibration, Uncertainty, and Robustness

This repository contains the full implementation and experimental pipeline for **Trust-STROKE**, a trustworthy machine learning framework for reliable stroke risk prediction from tabular health data.

Unlike conventional predictive models that focus only on discrimination performance, Trust-STROKE jointly evaluates **predictive accuracy, probabilistic calibration, epistemic uncertainty, robustness, clinical utility, and interpretability**, aiming to provide a clinically reliable and deployable risk prediction system.

---

## Overview

Reliable clinical prediction requires more than accurate classification. A clinically useful model must:

- Produce **calibrated probabilities**
- Provide **meaningful uncertainty estimates**
- Remain stable under **data variability and perturbations**
- Offer **clinically interpretable risk stratification**
- Demonstrate **decision-level clinical benefit**

Trust-STROKE integrates these aspects into a unified framework and evaluates performance under realistic imbalanced conditions.

---

## Key Contributions

- Unified trustworthy learning framework for stroke risk prediction
- Calibration-aware probability estimation using temperature scaling
- Ensemble-based epistemic uncertainty estimation
- Reliability-centric evaluation beyond conventional metrics
- Clinical utility assessment via decision curve analysis and risk stratification
- Robustness evaluation under adversarial perturbations and missingness stress
- Interpretability through global and local feature attribution
- Comprehensive reproducible experimental pipeline

---

## Dataset

This study uses a publicly available stroke risk prediction dataset:

**Mendeley Data Repository**  
https://data.mendeley.com/datasets/xggs239bnw/1  

The dataset contains anonymized tabular health records and has been widely used for stroke risk prediction research.

---

## Main Notebook

This notebook reproduces:

- Model training
- Calibration
- Uncertainty estimation
- Reliability analysis
- Decision curve analysis
- Robustness experiments
- Interpretability analysis

Additional notebooks in the repository provide intermediate experiments and extended analysis.

---

## Evaluation Dimensions

### Predictive Performance
- Precision–Recall AUC (PR-AUC)
- ROC-AUC
- Sensitivity, Specificity, F1-score
- Minority-event detection performance

### Calibration & Reliability
- Expected Calibration Error (ECE)
- Brier Score
- Negative Log-Likelihood
- Reliability diagrams

### Epistemic Uncertainty
- Uncertainty–error alignment
- Risk–coverage behavior
- High-confidence incorrect analysis
- Predictive stability

### Clinical Utility
- Decision curve analysis
- Population risk stratification
- Net clinical benefit

### Robustness
- Adversarial feature perturbations
- Targeted missingness stress testing
- Graceful degradation analysis

### Interpretability
- Global feature importance
- Local explanation analysis
- Clinically coherent risk drivers

## Repository Structure

├── stroke-prediction-final(2).ipynb # Main experimental pipeline
├── stroke-prediction-new-research-01.ipynb
├── stroke-prediction-new-research-02.ipynb
├── stroke-prediction-03.ipynb
├── stroke-prediction-04.ipynb
├── outputs/
│ ├── figures/
│ ├── tables/
│ ├── metrics/
│ └── predictions/
├── README.md
