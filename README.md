# Ferroptosis-Targeted Therapeutics for Oxaliplatin-Induced Peripheral Neuropathy (OIPN)

### A PRISMA-Compliant Systematic Literature Review & Meta-analysis

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Data_Visualization-orange)
![PRISMA](https://img.shields.io/badge/PRISMA-2020-success)
![Rayyan AI](https://img.shields.io/badge/Rayyan-AI-purple)
![License](https://img.shields.io/badge/License-Academic-lightgrey)

---

## Overview

Oxaliplatin-Induced Peripheral Neuropathy (OIPN) is a common dose-limiting toxicity of oxaliplatin-based chemotherapy. Emerging evidence implicates **oxidative stress**, **lipid peroxidation**, **mitochondrial dysfunction**, and **ferroptosis** as major contributors to its pathogenesis.

While no randomized clinical trial has directly investigated **5-Lipoxygenase (5-LOX) inhibition** for OIPN, multiple pharmacological agents targeting related oxidative and ferroptosis-associated pathways have been evaluated clinically.

This repository contains a **PRISMA 2020-compliant Systematic Literature Review (SLR) and Meta-analysis** that synthesizes the available clinical evidence and identifies the translational gap supporting future investigation of **Zileuton (5-LOX inhibitor)**.

---

# Objectives

* Perform a systematic review of randomized controlled trials evaluating ferroptosis-related interventions for OIPN.
* Quantitatively estimate the pooled treatment effect using meta-analysis.
* Evaluate between-study heterogeneity and publication bias.
* Identify current evidence gaps in ferroptosis-targeted therapy.
* Provide a clinical rationale for future preclinical studies investigating 5-LOX inhibition.

---

# Research Question

**Can pharmacological interventions targeting oxidative stress and the ferroptosis/lipid-peroxidation pathway reduce the incidence of Oxaliplatin-Induced Peripheral Neuropathy compared with placebo or standard care?**

---

# PICO Framework

| Component        | Description                                                         |
| ---------------- | ------------------------------------------------------------------- |
| **Population**   | Adult patients receiving oxaliplatin-based chemotherapy             |
| **Intervention** | Ferroptosis-related pharmacological agents                          |
| **Comparison**   | Placebo, standard supportive care, or chemotherapy alone            |
| **Outcome**      | Incidence of Chemotherapy-Induced Peripheral Neuropathy (CIPN/OIPN) |

---

# Included Pharmacological Interventions

* Glutathione
* Alpha-Lipoic Acid
* Vitamin E (Tocopherol)
* N-Acetylcysteine (NAC)
* Omega-3 Fatty Acids
* Calcium/Magnesium Infusions

These interventions were selected because they modulate oxidative stress, glutathione homeostasis, lipid peroxidation, mitochondrial integrity, or ferroptosis-related mechanisms.

---

# Methodology

The review was conducted according to the **PRISMA 2020 Statement**.

## Literature Search

**Database**

* PubMed

**Workflow**

1. Database search
2. Deduplication
3. Title & Abstract Screening
4. Full-text Review
5. Eligibility Assessment
6. Data Extraction
7. Quantitative Meta-analysis

---

## Study Screening

### Rayyan AI

The systematic review screening process was performed using **Rayyan AI**, which facilitated:

* Duplicate detection
* Title and abstract screening
* Blind reviewer decisions
* Conflict resolution
* Eligibility management
* Full-text selection workflow

---

## Statistical Analysis

Meta-analysis was performed using a **Random Effects Model** with the **Inverse Variance Method**.

### Outcome Measure

* Hazard Ratio (HR)
* 95% Confidence Interval

---

## Data Analysis & Visualization

Python was used for statistical visualization and generation of publication-quality figures.

### Libraries

* Python 3
* Matplotlib
* NumPy
* Pandas

Matplotlib was used to produce publication-ready visualizations, including:

* Forest Plot
* Funnel Plot
* Effect Size Visualization
* Confidence Interval Graphics

---

# Eligibility Criteria

## Inclusion

* Randomized Controlled Trials (RCTs)
* Adult cancer patients receiving oxaliplatin-containing chemotherapy
* Pharmacological interventions targeting oxidative stress or ferroptosis-related pathways
* Binary neuropathy outcomes with extractable event data

## Exclusion

* Non-randomized studies
* Animal or in vitro studies
* Non-pharmacological interventions
* Studies without extractable incidence data
* Non-oxaliplatin chemotherapy populations

---

# Results

## Studies Included

**7 Randomized Controlled Trials**

---

## Pooled Effect

| Statistic    | Value          |
| ------------ | -------------- |
| Hazard Ratio | **0.56**       |
| 95% CI       | **0.37–0.84**  |
| Model        | Random Effects |

The pooled analysis demonstrated a statistically significant reduction in the risk of chemotherapy-induced peripheral neuropathy among patients receiving ferroptosis-related pharmacological interventions.

---

## Heterogeneity

| Metric | Value   |
| ------ | ------- |
| I²     | **66%** |

Moderate-to-high heterogeneity indicates variability across intervention types, patient populations, and study methodologies.

---

## Publication Bias

Publication bias was evaluated using:

* Funnel Plot
* Egger's Regression Test

### Findings

* No significant funnel plot asymmetry
* Egger's regression not statistically significant

Overall, the included evidence does not indicate substantial publication bias.

---

# Key Findings

* Ferroptosis-related interventions significantly reduce OIPN incidence.
* Oxidative stress and lipid peroxidation remain promising therapeutic targets.
* No published randomized clinical trial has evaluated a **5-Lipoxygenase inhibitor** for OIPN.
* This unmet clinical evidence supports further investigation of **Zileuton** as a novel therapeutic candidate.

---

# Repository Structure

```text
.
├── Search_Strategy/
├── PRISMA/
├── Rayyan_AI/
├── Full_Text_Review/
├── Data_Extraction/
├── Statistical_Analysis/
├── Meta_Analysis/
├── Forest_Plot/
├── Funnel_Plot/
├── Python/
│   ├── forest_plot.py
│   ├── funnel_plot.py
│   ├── data_processing.py
│   └── visualization.py
├── Figures/
├── Results/
├── README.md
└── LICENSE
```

---

# Technologies Used

| Category             | Tools                        |
| -------------------- | ---------------------------- |
| Literature Search    | PubMed                       |
| Screening            | Rayyan AI                    |
| Guidelines           | PRISMA 2020                  |
| Data Extraction      | Microsoft Excel              |
| Statistical Analysis | Random Effects Meta-analysis |
| Programming          | Python                       |
| Visualization        | Matplotlib                   |
| Version Control      | Git & GitHub                 |

---

# Future Work

* Risk of Bias (RoB 2) assessment
* GRADE certainty of evidence
* Sensitivity analyses
* Subgroup analyses
* Expansion to additional oxidative stress-related therapeutic targets
* Integration with the ongoing preclinical evaluation of **Zileuton** in experimental OIPN models

---

# Citation

If you use this repository in your research, please cite the associated dissertation or future peer-reviewed publication.

---

# License

This repository is shared for **academic and research purposes**. Please provide appropriate attribution when using or adapting the materials.

---

## Acknowledgements

* PRISMA 2020 Reporting Guidelines
* PubMed (Literature Search)
* Rayyan AI (Study Screening)
* Python & Matplotlib (Statistical Visualization)
* GitHub (Version Control & Project Hosting)
