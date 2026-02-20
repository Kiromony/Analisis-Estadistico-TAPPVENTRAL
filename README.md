# Clinical Statistical Analysis of Ventral Hernia Repair Outcomes

Independent statistical consulting project analyzing surgical outcomes from a retrospective cohort of patients undergoing laparoscopic ventral hernia repair (TAPP technique).

## Overview

This project involved the complete statistical analysis of a clinical dataset comprising 162 patients treated at a tertiary medical center. The objective was to identify risk factors associated with hernia recurrence and to characterize the surgical population through rigorous statistical methodology.

The analysis was conducted independently in collaboration with a medical researcher (Ph.D. candidate), who provided clinical context and domain-specific interpretation.

The final report was used for clinical evaluation and research purposes.

---

## Objectives

- Characterize demographic and clinical features of the surgical cohort
- Quantify recurrence rates and identify associated risk factors
- Evaluate statistical relationships between clinical variables and surgical outcomes
- Produce publication-quality statistical figures and technical report

---

## Methodology

The analysis pipeline was implemented entirely in Python.

### Statistical tools and libraries used

- pandas — data manipulation and preprocessing
- scipy.stats — statistical hypothesis testing
- seaborn — statistical visualization
- matplotlib — figure generation

### Statistical tests performed

Due to non-normal distributions and small subgroup sizes, non-parametric statistical tests were used:

- Mann–Whitney U test — comparison of continuous variables
- Fisher’s exact test — comparison of categorical variables
- Odds ratio estimation — risk quantification

---

## Key Findings

- Overall recurrence rate: **4.9%**
- Patients with prior hernia recurrence had significantly higher risk of recurrence:
  - Odds ratio: **10.95**
  - p-value: **0.011**
- Surgical complexity was significantly associated with increased operative time:
  - p-value: **0.0037**
- Emergency surgery showed elevated recurrence trends but did not reach statistical significance due to limited sample size

---

## Deliverables

- Complete statistical analysis pipeline in Python
- Clinical interpretation of results
- Publication-quality figures and plots
- Formal technical report provided to medical researcher

---

## Repository Contents

scripts/ # Statistical analysis code with visualizations (included in report)
papers/ # Useful documentation for this work
report/ # Final technical report
README.md # Project documentation


---

## Data Availability

Clinical data is not included in this repository due to privacy and confidentiality constraints.

All code is designed to operate on anonymized datasets with equivalent structure.

---

## Skills Demonstrated

- Statistical inference
- Clinical data analysis
- Non-parametric statistical testing
- Scientific reporting
- Data visualization
- Independent consulting and project ownership

---

## Author

Simón Repolt Lazo  
MSc Data Science — Universidad de Chile  
Electrical Engineer  

GitHub: https://github.com/Kiromony  
Email: simon@repolt.net

---

## Disclaimer

This repository contains analysis code and report produced as part of an independent statistical consulting project. No confidential patient data is included.