# Physics-Guided-Inverse-Design-of-High-Tc-Spintronic-Materials
Interpretable, physics-guided machine learning framework for Curie temperature prediction and inverse design of spintronic materials.
# Physics-Guided Inverse Design of High-Curie-Temperature Spintronic Materials

This repository contains the complete data and code accompanying the manuscript:

"Interpretable Machine Learning for Physics Guided Inverse Design of High Curie Temperature Spintronic Materials"

## Overview

We present an interpretable, physics-informed machine learning framework that:

- Predicts Curie temperatures (Tc) of magnetic materials
- Benchmarks multiple ML models (XGBoost, LightGBM, Random Forest, MLP)
- Uses SHAP-based interpretability and chemistry-resolved error analysis
- Performs physics-constrained inverse materials design
- Screens candidates using spintronics-oriented proxy metrics

The workflow is fully reproducible and designed for transparent materials discovery.

---

## Repository Structure

```text
.
├── Curie_Tc_Spintronics.ipynb   # Main reproducible notebook
├── data/
│   ├── raw/                    # Input datasets
│   └── intermediate/           # Feature tables
├── results/
│   ├── figures/                # All generated figures (PNG/PDF)
│   ├── tables/                 # CSV tables
│   ├── shap/                   # SHAP outputs
│   └── inverse_design/         # Inverse design candidates
├── requirements.txt            # Python dependencies
└── README.md
