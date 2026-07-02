![Python](https://img.shields.io/badge/Python-3.10+-blue)
![Trustworthy AI](https://img.shields.io/badge/Trustworthy-AI-green)
![Causal AI](https://img.shields.io/badge/Causal-AI-orange)
![Dataset](https://img.shields.io/badge/Dataset-NASA%20C--MAPSS-red)
![License](https://img.shields.io/badge/License-MIT-brightgreen)

# Trustworthy Causal AI System for Predictive Maintenance using NASA C-MAPSS

## Overview

This project presents a research-oriented **Trustworthy Causal AI framework** for predictive maintenance using the NASA C-MAPSS turbofan engine degradation dataset.

Unlike conventional Remaining Useful Life (RUL) prediction systems, this work extends predictive maintenance toward **causal reasoning**, **structural causal modelling**, **counterfactual analysis**, and **maintenance decision support**, enabling more transparent and interpretable industrial AI.

The project follows the complete research pipeline:

**Prediction → Explainability → Temporal Causal Discovery → Structural Causal Modeling → Counterfactual Reasoning → Maintenance Decision Support**

---

# Research Objectives

This project investigates how industrial AI systems can move beyond accurate prediction to answer practical engineering questions such as:

- Why is the engine degrading?
- Which sensors drive degradation?
- Which variables are causal rather than merely correlated?
- What maintenance intervention would improve engine health?
- How confident is the AI system in its recommendations?

---

# Dataset

**NASA Commercial Modular Aero-Propulsion System Simulation (C-MAPSS)**

Dataset Used:

- FD001 Training Dataset
- FD001 Testing Dataset
- Remaining Useful Life (RUL) Labels

Dataset contains:

- 100 training engines
- 100 testing engines
- 21 sensor measurements
- Operational settings
- Complete engine degradation trajectories

---

# Project Pipeline

The repository consists of eight research notebooks:

| Notebook | Description |
|----------|-------------|
| 01 | Data Understanding & Industrial Causal Framing |
| 02 | Remaining Useful Life Engineering |
| 03 | Baseline Causal Structure Discovery |
| 04 | Trustworthy AI Prediction & Explainability |
| 05 | Temporal Causal Discovery using Granger Causality |
| 06 | Structural Causal Model (SCM) Construction |
| 07 | Structural Equation Modelling (SEM) |
| 08 | Counterfactual Reasoning & Maintenance Decision Support |

---

# Key Features

- Remaining Useful Life Prediction
- Explainable AI
- Temporal Causal Discovery
- Structural Causal Modelling
- Structural Equation Modelling
- Counterfactual Maintenance Simulation
- Sensor Influence Analysis
- Maintenance Decision Support
- Trustworthy Industrial AI Framework

---

# Results

The framework generates:

- Remaining Useful Life predictions
- Sensor importance rankings
- Temporal causal graphs
- Structural causal models
- Structural equation models
- Counterfactual intervention analysis
- Maintenance priority recommendations
- Industrial decision-support outputs

---

# Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NetworkX
- Statsmodels

---

# Research Contributions

This work demonstrates an end-to-end industrial AI pipeline that combines:

- Machine Learning
- Explainable AI
- Temporal Causal Discovery
- Structural Causal Modelling
- Counterfactual Reasoning

to support trustworthy predictive maintenance for complex engineering systems.

---

# Future Work

Potential extensions include:

- Dynamic Bayesian Networks
- Do-Calculus based intervention analysis
- Causal Reinforcement Learning
- Digital Twin Integration
- Real-time Industrial Deployment

---

# Citation

**Dataset**

Saxena, A., & Goebel, K. (2008).  
*Turbofan Engine Degradation Simulation Data Set.*  
NASA Prognostics Data Repository.

https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/

---

# License

Released under the MIT License.
