# An Exploratory Study to Find the Early Trend and Pattern Recognition of COVID-19 Infection in India: A Severity Model-Based Prediction

**Afreen Khan**, S. Zubair, N. Khalique, S. Khan  
*Indian Journal of Community Health*, 2021  

🔗 **Paper (PDF):** https://www.iapsmupuk.org/journal/index.php/IJCH/article/view/2033/1175

---

## Overview

This repository serves as a **research companion** to the published article titled  
*“An Exploratory Study to Find the Early Trend and Pattern Recognition of COVID-19 Infection in India: A Severity Model-Based Prediction.”*

The study investigates early temporal trends of COVID-19 infection in India using exploratory data analysis and severity-oriented analytical modeling. By combining descriptive epidemiological analysis with logistic growth modeling, the work aims to identify early inflection points, characterize growth dynamics, and support short-term prediction of confirmed cases during the initial phase of the pandemic.

This repository documents the **methodological framework, analytical workflow, and key findings** reported in the paper. It does not provide a real-time forecasting system or a fully reproducible modeling pipeline.

---

## Study Design and Data Sources

The analysis is based on publicly available, aggregate-level COVID-19 case data reported for India during the early phase of the pandemic. The study adopts an observational, retrospective design, focusing on national-level trends rather than individual-level clinical outcomes.

Reported case counts—including confirmed, recovered, and deceased cases—were used to derive growth indicators and severity-related metrics. All analyses were conducted in accordance with publicly accessible data usage policies.

No patient-level or sensitive health records are included or distributed through this repository.

---

## Exploratory Data Analysis

Exploratory Data Analysis (EDA) was employed to examine temporal patterns and underlying dynamics in COVID-19 case progression. The analysis includes:

- Cumulative case trends over time  
- Weekly growth patterns  
- Growth ratio and growth factor estimation  
- Identification of early acceleration and deceleration phases  

EDA served as a foundational step for understanding epidemic behavior prior to formal modeling and for informing the selection of suitable growth functions.

---

## Severity Model and Logistic Growth Analysis

To capture the progression of COVID-19 infection in India, a severity-based analytical framework was adopted. Logistic growth modeling was used to characterize epidemic expansion and estimate key epidemiological indicators, including the inflection point corresponding to peak growth acceleration.

The logistic growth curve enables interpretation of outbreak dynamics in terms of early exponential growth, transitional phases, and eventual stabilization. This approach provides an interpretable mathematical representation of epidemic severity trends rather than purely data-driven forecasting.

---

## Key Findings

The analysis highlights distinct early growth patterns in COVID-19 infection trends across India. Growth ratio and growth factor metrics revealed periods of rapid escalation followed by gradual stabilization.

Logistic growth modeling enabled estimation of inflection points indicative of shifts in epidemic progression. These findings underscore the value of early exploratory analysis combined with interpretable growth models in supporting public health situational awareness during emerging outbreaks.

The study emphasizes that severity-oriented analytical modeling can complement surveillance efforts by providing early insights into epidemic trajectories.

---

## Repository Scope and Limitations

This repository is intended for **methodological documentation and analytical interpretation** only.

- Original experimental code and raw datasets are not publicly released.
- The repository does not provide real-time prediction or policy simulation tools.
- Visualizations included are illustrative summaries derived from reported results.

The focus is on transparency of analytical reasoning rather than computational reproducibility.

---

## Citation

If you use or reference this work, please cite the original publication:

```bibtex
@article{khan2021covidseverity,
  title={An Exploratory Study to Find the Early Trend and Pattern Recognition of COVID-19 Infection in India: A Severity Model-Based Prediction},
  author={Khan, Afreen and Zubair, S. and Khalique, N. and Khan, S.},
  journal={Indian Journal of Community Health},
  year={2021}
}
