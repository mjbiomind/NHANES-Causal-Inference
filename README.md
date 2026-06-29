# Causal Inference Pipeline: Disentangling SDoH & Inflammatory Biomarkers
**Project Track:** Computational Psychiatry & Health Disparities  
**Principal Analyst:** Mary Jacobs ([MJBIOMIND](https://linkedin.com))  
**Academic Affiliation:** Stanford University (Medical Statistics Framework)  

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

## 🔒 Intellectual Property & Repository Governance
To prevent unauthorized replication, safeguard proprietary data engineering pipelines, and maintain strict academic data security, the comprehensive production-grade scripts, live source code blocks, and full structural dictionaries for this project are **classified**.

### 📄 Document Registry Status:
- [x] Methodology Abstract & Mathematical Formulation (Visible)
- [ ] Production Python Pipeline (`causal_ptsd_nhanes.py`) -> **[RESTRICTED]**
- [ ] Local Environment Architecture (`environment.yml`) -> **[RESTRICTED]**
- [ ] Detailed Parameter Codebook (`DATA_DICTIONARY.md`) -> **[RESTRICTED]**
- [ ] Comprehensive Interpretation Summary (`OUTPUT_REPORT.md`) -> **[RESTRICTED]**

### 🔑 Requesting Technical Access
Full source-code access, verification logs, and reproducible environment wrappers will be provisioned strictly to verified Principal Investigators, academic committees, and clinical data directors. 

To request credentials to audit the live repository assets, please submit a formal professional validation request via **[LinkedIn Direct Message](https://www.linkedin.com/in/mjbiomind/)**.

---
> *"Using data to understand people, using science to reduce suffering, and using knowledge to build a life of lasting impact."*
