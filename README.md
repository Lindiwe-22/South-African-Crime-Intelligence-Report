# 🔍 South African Crime Intelligence Report
## Gender-Based Violence, Sexual Offences & Femicide: A Critical Data Analysis™

> *"Crime remains unacceptably high and continues to affect many families
> and communities."*
> — Acting Police Minister Firoz Cachalia, 20 February 2026

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![SAPS](https://img.shields.io/badge/Data-SAPS%20Official-green)
![SAMRC](https://img.shields.io/badge/Data-SAMRC%202025-red)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-lightgrey)

---

## 🎯 Project Overview

This notebook interrogates the claim by SAPS Crime Registrar
Major-General Thulare Sekhukhune that reported rape cases decreased
by 3.2% in Q3 FY2025/26 — and places that claim within two decades
of femicide surveillance data published by the South African Medical
Research Council (SAMRC).

Produced from the perspective of a **private security analytical
division** conducting occasional work with SAPS, this notebook
applies rigorous data science methodology to one of South Africa's
most critical public health and safety challenges.

---

## ❓ Research Questions

1. Is there truly a decrease in reported rape as stated by
   Maj-Gen Sekhukhune?
2. What does the SAMRC's 20-year femicide surveillance data
   reveal that SAPS statistics cannot?
3. Which provinces and demographics are at highest risk?
4. What does statistical modelling predict for FY2025/26
   and FY2026/27?

---

## 📓 Notebook Structure

| Phase | Cells | Content |
|-------|-------|---------|
| **Phase 1** | 1–2   | Environment setup, CSV data pipeline |
| **Phase 2** | 3–10  | Exploratory data analysis — 8 visualisation panels |
| **Phase 3** | 11–15 | Statistical modelling — correlation, anomaly detection, regression, forecasting |
| **Phase 4** | 16–19 | Intelligence report, dashboard, recommendations |

---

## 🔬 Methods Applied

- Pearson & Spearman correlation analysis
- Z-score anomaly detection (annual + provincial)
- Isolation Forest anomaly detection
- OLS regression — simple & multiple with full diagnostics
- Linear extrapolation with 95% prediction intervals
- Holt's Exponential Smoothing
- ARIMA(1,1,0) with confidence intervals
- 3-model ensemble forecasting

---

## 📊 Data Sources

| Source | Description | Period |
|--------|-------------|--------|
| SAPS Q3 2025/26 | Cachalia press briefing, 20 Feb 2026 | Oct–Dec 2025 |
| SAPS Annual Reports | Historical crime statistics | FY2012/13–FY2023/24 |
| SAMRC Femicide Study | Abrahams et al. (2025), Global Public Health | 1999–2020/21 |
| Africa Check | Underreporting research | Various |
| Stats SA | Mid-year population estimates | 2013–2025 |

---

## 🗂️ Repository Structure
```
sa-crime-intelligence/
├── SA_Crime_Intelligence_Report.ipynb   # Main notebook
├── intelligence_dashboard.png           # Exported dashboard
├── data/
│   ├── quarterly_rape.csv
│   ├── annual_sexual_offences.csv
│   ├── contact_crimes_q3.csv
│   ├── provincial_rape.csv
│   ├── femicide_samrc.csv
│   └── underreporting_estimates.csv
└── README.md
```

---

## 🔑 Key Findings

**On the reported rape decrease:**
A 3.2% decline in reported rape (373 fewer cases) does NOT
constitute evidence of reduced sexual violence. Three provinces
recorded increases, and underreporting research estimates only
1 in 25 rapes reaches SAPS records.

**On femicide (SAMRC, 2025):**
South Africa's intimate partner femicide rate of 5.5 per 100,000
women is five times the global average. This rate INCREASED during
COVID-19 and has not structurally declined since 2009.

**On the forecast:**
Ensemble modelling (Linear + Holt's ES + ARIMA) projects no
structural decline in the rape rate for FY2025/26 or FY2026/27.

---

## 🛠️ Tech Stack

| Category | Tools |
|----------|-------|
| Data manipulation | Python, Pandas, NumPy |
| Visualisation | Matplotlib, Seaborn |
| Statistical analysis | SciPy, Statsmodels |
| Machine learning | Scikit-learn (Isolation Forest) |
| Time series | Statsmodels (Holt's ES, ARIMA) |
| Environment | Google Colab |

---

## ⚠️ Important Disclaimer

All data used is sourced from publicly available official government
publications and peer-reviewed research. This notebook does not
contain classified or confidential SAPS operational data. Findings
represent the independent analytical conclusions of the author.

---

## 👩🏾‍💻 Author

**Lindiwe Songelwa™** — Data Scientist | Developer | Insight Creator

- 🌐 [Portfolio](https://lindiwe-22.github.io/Portfolio-Website/)
- 💼 [LinkedIn](https://www.linkedin.com/in/lindiwe-songelwa)
- 🏅 [Credly](https://www.credly.com/users/samnkelisiwe-lindiwe-songelwa)
- 📧 sl.songelwa@hotmail.co.za

---

© 2026 Lindiwe Songelwa™. All rights reserved.
*No part of this work may be reproduced without express written
permission of the author.*
