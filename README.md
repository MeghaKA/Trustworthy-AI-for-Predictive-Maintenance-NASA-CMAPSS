# Trustworthy Causal AI System for Predictive Maintenance using NASA C-MAPSS


## Overview

This project develops a trustworthy industrial AI framework for predictive maintenance using the NASA C-MAPSS turbofan engine degradation dataset.

The objective is to move beyond traditional failure prediction models by integrating:

- Remaining Useful Life (RUL) prediction
- Explainable AI
- Sensor degradation analysis
- Causal AI reasoning framework
- Prediction uncertainty estimation


The project follows the research direction:

Prediction → Explanation → Causal AI Reasoning


---

# Research Motivation

Industrial predictive maintenance systems can forecast failures, but real-world deployment requires deeper understanding:

- Why is the system degrading?
- Which variables influence failure progression?
- How confident is the AI prediction?
- What interventions could reduce maintenance risk?


This project explores the transition from predictive machine learning toward trustworthy causal industrial AI.


---

# Dataset

Dataset:

NASA Commercial Modular Aero-Propulsion System Simulation (C-MAPSS)


Dataset characteristics:

- Turbofan engine degradation simulation
- Multiple engine units
- Time-series sensor measurements
- Progressive failure behaviour


Features:

- Engine ID
- Operating cycle
- Operational settings
- 21 sensor measurements


Dataset used:

FD001 subset


Training engines:
100

Testing engines:
100


---

# Project Structure

Trustworthy-Causal-AI-Predictive-Maintenance-NASA-CMAPSS

│
├── data
│   └── raw
│       └── synapse_data
│           ├── train_FD001.txt
│           ├── test_FD001.txt
│           └── RUL_FD001.txt
│
├── notebooks
│
│   ├── 01_Data_Understanding_Causal_Framing.ipynb
│
│   ├── 02_RUL_Engineering_Predictive_Maintenance.ipynb
│
│   ├── 03_Causal_Structure_Discovery.ipynb
│
│   └── 04_Trustworthy_Causal_AI_Final_System.ipynb
│
├── README.md
├── requirements.txt
└── LICENSE

---

# Methodology


## Notebook 01
### Data Understanding & Causal Framing

Performed:

- Dataset exploration
- Engine lifecycle analysis
- Sensor behaviour analysis
- Degradation pattern identification


---

## Notebook 02
### Remaining Useful Life Engineering

Performed:

- RUL calculation
- Predictive target creation
- Sensor degradation relationship analysis


RUL formulation:

RUL = Maximum engine cycle - Current cycle


---

## Notebook 03
### Causal Structure Discovery Foundation

Performed:

- Sensor normalization
- Dependency analysis
- Causal assumptions
- Industrial causal hypothesis graph


Conceptual causal flow:


Operational Conditions

↓

Sensor Dynamics

↓

Engine Degradation

↓

RUL

↓

Failure


---

## Notebook 04
### Trustworthy Causal AI Final System


Implemented:

- Random Forest predictive model
- Unseen engine evaluation
- Explainability
- Prediction uncertainty estimation


Model results:


RMSE:
46.24 cycles


MAE:
34.87 cycles


R²:
0.385



---

# Key Findings

The developed industrial AI pipeline successfully:

- Processes raw turbofan telemetry data
- Predicts remaining useful life
- Identifies important degradation-related sensors
- Estimates prediction confidence


Important insight:

Feature importance indicates predictive influence, not causal influence.


Therefore trustworthy industrial AI requires:

Prediction + Explanation + Causal Understanding


---

# Critical Insight

Industrial systems are complex.

A model may predict failure accurately but still cannot answer:

"Why did failure happen?"

"What factor caused degradation?"

"What intervention could reduce risk?"


Future extensions:

- Structural Causal Models (SCM)
- Granger causality
- Temporal causal discovery
- Counterfactual maintenance simulation
- Digital twin based interventions


---

# Technologies

Python

Libraries:

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- NetworkX


Machine Learning:

- Random Forest Regression


AI Areas:

- Industrial AI
- Predictive Maintenance
- Explainable AI
- Causal AI
- Trustworthy AI


---

# Research Direction

This project provides a foundation for PhD-level research in:

- Causal Machine Learning
- Industrial AI
- Intelligent Maintenance Systems
- Trustworthy Decision Support Systems

---

# Reproducibility

All experiments were developed using Python-based machine learning workflows.

The project structure, notebooks, and requirements file are provided to support reproducibility and further research exploration.


---


# Citation

If you use this project or the methodology for research, please cite the following:

## Dataset Citation

Saxena, A., & Goebel, K. (2008).  
*Turbofan Engine Degradation Simulation Data Set.*  
NASA Ames Research Center, NASA Prognostics Data Repository.

Available at:
https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/


## Project Citation

Trustworthy Causal AI System for Predictive Maintenance using NASA C-MAPSS.

GitHub Repository.

A research implementation exploring:
- Remaining Useful Life prediction
- Explainable Industrial AI
- Trustworthy AI for predictive maintenance
- Causal reasoning frameworks for machine degradation analysis


---


# License

This project is released under the MIT License.

You are free to use, modify, and distribute this project with appropriate attribution.
