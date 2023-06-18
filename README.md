# Atrial-fibrillation-risk-prediction
Script to compute different atrial fibrillation risk prediction scores
To compute the scores run the jupyter notebook file (Atrial_fibrillation_risk_scores.ipynb) in colab or locally.
## Description

Scores | Italian score	| Mayo score	| Treatment-aware | Treatment-aware with interaction*
--- |--- | --- | --- | ---
Aim	| Prevalence and risk factors of AF in a cohort of ibrutinib-naive CLL| Prevalence of AF in a general cohort of CLL | Prevalence and risk factors of AF in a cohort of CLL | Prevalence and risk factors of AF in a cohort of CLL
 -| Validated on a cohort of ibrutinib-treated patients | - | Ibrutinib and other treatment types included | Ibrutinib and other treatment types included
Prediction point | Diagnosis | Diagnosis	| Treatment initiation | Treatment initiation
Risk factors | | | |
Age ≥ 65 | 1 | 2 | 1 | 1 (2)
Age ≥ 75 |   | 1 | 1 | 1 (2)
Male sex | 1 | 1 | 1 | 1 (2)
Hypertension |  | 1 | 1 | 1 (2)
Cardiopathy | 3 |  | |
Valvular heart diseases | 2 | 2 | 1 | 1
Hypo/hyperthyroidism | 2 |  |  |
Chronic lung diseases | 1 |  | |
Type-2 diabetes | 1 |  | 1 | 1 (2)
Grade ≥ 3 infections | 1 |  | |
Blood culture (count) | | | 1 | 1 (2)
Blood culture (positive) | | | 1 | 1 (2)
Ibrutinib treatment | | | 1 | 1
* **The score in the parenthesis applies if treated with ibrutinib**
