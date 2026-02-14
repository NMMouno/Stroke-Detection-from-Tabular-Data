
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

---

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
