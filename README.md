# Trust-Aware Explainable AI for Pneumonia Detection

## Overview
This repository provides a fully reproducible implementation of a trust-aware, explainable AI framework for pneumonia detection. The approach integrates predictive modeling, calibration analysis, threshold-based decision-making, and multi-level explainability to support clinically meaningful decision support.

## Key Features
- High-sensitivity pneumonia detection under class imbalance
- Calibration-aware probability modeling
- Threshold-dependent clinical decision analysis
- Multi-level explainability:
  - SHAP (global feature importance)
  - LIME (local explanations)
  - Counterfactual sensitivity analysis
- Full pipeline reproducibility (figures, tables, outputs)

## Methodology
The framework follows a structured pipeline:
1. Data preprocessing and feature structuring
2. Train–test partitioning with stratification
3. Model training (Logistic Regression, Random Forest, XGBoost, LightGBM)
4. Model selection using cross-validation
5. Threshold-aware decision optimization
6. Explainability analysis (SHAP, LIME, sensitivity)
7. Calibration and performance evaluation

## Results
- AUC: 0.70
- Recall (high-sensitivity regime): up to 0.90
- Precision–Recall trade-off under imbalance
- Calibration deviations identified and analyzed

## Explainability
- Global feature importance aligned with clinical knowledge
- Local patient-level explanations for decision transparency
- Actionable insights via sensitivity analysis

## Reproducibility
All results are generated through structured notebooks:
- Figures (ROC, PR, calibration, SHAP, LIME)
- Tables (performance, confusion matrix, thresholds)
- outputs_summary.txt for quick evaluation

## Citation
If you use this repository, please cite:

@misc{Hamam2026PneumoniaXAI,
  author = {H. Hamam},
  title = {Trust-Aware Explainable AI Framework for Pneumonia Detection},
  year = {2026},
  howpublished = {GitHub repository},
  note = {Reproducible pipeline with calibration, explainability, and decision-support analysis}
}

## License
MIT License

## Contact
For research collaboration or inquiries, please contact:
habib.hamam@umoncton.ca
