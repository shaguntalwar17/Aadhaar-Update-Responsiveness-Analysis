# Aadhaar Update Responsiveness Analysis  
## Measuring Identity Dormancy as a Hidden Driver of Welfare Exclusion

## Overview

Aadhaar has achieved near-universal enrolment across India, yet authentication failures continue to affect welfare delivery. This project argues that the core challenge is not enrolment coverage, but update responsiveness.

Using aggregated Aadhaar enrolment, demographic update, and biometric update datasets, this study identifies identity dormancy as a structural vulnerability within welfare systems. It introduces a quantitative framework to measure how effectively identity records evolve relative to enrolment scale.

---

## Problem Statement

High enrolment numbers often conceal low update activity. When demographic and biometric records fail to evolve with citizens’ lives, authentication systems that depend on real-time verification fail silently.

The objective of this project is to shift the evaluation of identity systems from coverage saturation to maintenance responsiveness.

---

## Core Contribution

### State-wise Update Responsiveness Index (SURI)

SURI is a system-level metric designed to measure identity maintenance relative to enrolment volume.

Formula:

SURI = ((Demographic Updates + Biometric Updates) / Total Enrolment) × (1 − Failure Rate)

The index is normalised to a 0–100 scale and functions as an early-warning indicator for detecting stagnant identity ecosystems.

---

## Key Findings

- Significant identity dormancy within adult Aadhaar records  
- Substantial gap between enrolment coverage and update activity  
- Wide inter-state disparities in update responsiveness  
- Adult maintenance lag despite higher exposure to migration and biometric degradation  

The findings demonstrate that enrolment does not guarantee inclusion.

---

## Methodology

The study follows a three-layer integrated framework:

1. Analytical Layer  
   - Data preprocessing and schema normalisation  
   - Temporal and geographic standardisation  
   - Update intensity and dormancy analysis  
   - SURI computation  

2. Visual Layer  
   - Interactive Power BI dashboard  
   - State-wise heatmaps  
   - KPI summaries  
   - Comparative update analysis  

3. Operational Layer  
   - Role-based system prototype  
   - Citizen tracking interface  
   - Authority workflow dashboard  
   - Administrative oversight panel  

---

## Technology Stack

- Python (Pandas, NumPy, Matplotlib, Seaborn)  
- Power BI  
- React (Prototype)  
- Google Colab  

---

## Repository Structure

data/  
notebooks/  
dashboard/  
prototype/  
report/  
README.md  

---

## Data Ethics and Compliance

All datasets used in this study are aggregated and anonymised. No personally identifiable information (PII) is processed. The system prototype operates on synthetic data and is intended for workflow demonstration only.

---

## Impact

This framework enables:

- Early detection of welfare exclusion risk  
- Monitoring of identity maintenance gaps  
- Evidence-based administrative intervention  
- Shift from reactive correction to proactive prevention  

The effectiveness of an identity system should be measured not by how many people it enrols, but by how reliably it continues to recognise them when needed.

---

## Author

Shagun  
UIDAI Data Hackathon 2026  
University of Petroleum and Energy Studies  

