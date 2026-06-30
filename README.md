# Causal Inference Pipeline: Disentangling SDoH & Inflammatory Biomarkers
**Project Track:** Computational Psychiatry & Health Disparities  
**Principal Analyst:** Mary Jacobs ([MJBIOMIND](https://linkedin.com))  

---

## 🔬 Core Hypothesis & Thesis
This project models the structural intersection of Social Determinants of Health (SDoH) and systemic biological inflammation markers. Rather than treating chronic environmental stress vectors and psychiatric conditions like PTSD or depression as independent static diagnoses, this pipeline treats them as an entangled, multi-system network. 

The primary statistical objective is to isolate and evaluate unconfounded interaction parameters to track how environmental trauma scales biological inflammatory indicators across historically minoritized Hispanic cohorts.

---

## 📊 Methodological Framework
To suppress baseline selection bias and handle confounding variables without exposing authentic clinical registries, the pipeline utilizes an advanced **Inverse Probability of Treatment Weighting (IPTW)** architecture executed via a mathematically sound, simulated distribution profile matching NHANES parameters:

1. **Propensity Score Mapping:** Baseline logistic regression models estimate the conditional probability vector $e(W)$ based on demographic and socioeconomic confounders ($W = \{\text{Age, Income-Poverty Ratio, Cohort Stratification}\}$).
2. **Pseudo-Population Balancing:** Observational vectors are converted using stabilized inverse probability weights ($w_i$) to construct a perfectly balanced pseudo-population matrix.
3. **Marginal Structural Estimation:** A Weighted Least Squares (WLS) regression model evaluates log-transformed C-Reactive Protein ($\log(\text{CRP})$) outcomes using an explicit intersectional causal multiplier term ($T \times X$).

---

### 📄 Open Source - Document Registry Status:
- [ ] Methodology Abstract & Mathematical Formulation 
- [ ] Production Python Pipeline (`causal_ptsd_nhanes.py`) 
- [ ] Local Environment Architecture (`environment.yml`)
- [ ] Detailed Parameter Codebook (`DATA_DICTIONARY.md`) 
- [ ] Comprehensive Interpretation Summary (`OUTPUT_REPORT.md`)

---
> *"Using data to understand people, using science to reduce suffering, and using knowledge to build a life of lasting impact."*
