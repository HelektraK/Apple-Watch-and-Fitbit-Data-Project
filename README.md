# Apple Watch and Fitbit Data Project

This project investigates whether demographic attributes (age and gender)
can be predicted from consumer wearable data using statistical analysis
and machine learning models.

We analyze heart rate, resting heart rate, heart rate variability (HRV),
step count, calories burned, and activity intensity data collected from
Apple Watch and Fitbit devices.

**Full paper:**  
[`paper/FitBit_Apple_Watch_Milestones.pdf`](paper/FitBit_Apple_Watch_Milestones.pdf)

---

## Project Overview

- **Task:** Predict age group and gender from wearable-derived features
- **Data source:** Harvard Dataverse (Apple Watch + Fitbit)
- **Models explored:**
  - Logistic Regression (baseline)
  - Random Forest
  - XGBoost
- **Key result:**  
  - Up to **97% accuracy** for gender prediction  
  - Up to **98.9% accuracy** for age-decade classification (XGBoost, CV)

---

## Methods (High Level)

- Exploratory Data Analysis (EDA)
- Statistical testing (ANOVA, ANCOVA)
- Supervised classification
- Stratified cross-validation
- Class imbalance handling

Details, figures, and full analysis are provided in the paper.

---

## Repository Contents

- `main.ipynb` — Data analysis and modeling notebook
- `paper/` — Final project paper (PDF)
- `.gitignore` — Excludes raw biometric data

---

## Data Availability

Raw wearable data is **not included** in this repository due to privacy
considerations. The analysis code assumes preprocessed feature tables
derived from the Harvard Dataverse dataset.

---

## Notes on Ethics and Bias

This project explicitly examines demographic prediction and discusses
fairness, class imbalance, and potential bias in wearable-device data.
See the Discussion and Future Directions sections of the paper for details.

---

## Authors

- Helektra Katsoulakis  
- Maria Mechery

Course: *COMPSCI 390B: Data Science for the Common Good (UMass Amherst)*