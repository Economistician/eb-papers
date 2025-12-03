# Cost-Weighted Service Loss (CWSL) — Long-Form Technical Paper  
**Electric Barometer Research Series — Paper No. 01**  

[![License: BSD-3](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](LICENSE)

---

## Overview

This repository hosts the long-form technical paper introducing  
**Cost-Weighted Service Loss (CWSL)** — a demand-normalized, asymmetric forecast  
evaluation metric designed for high-frequency, high-variance operational environments.  
CWSL directly incorporates the *directionality* of forecast error and the *operational  
cost asymmetry* between:

- **Shortfalls** (under-forecasting)
- **Overbuild** (over-forecasting)

Unlike symmetric metrics (RMSE, MAPE, wMAPE), CWSL is grounded in operational impact  
rather than abstract statistical deviation.

This work is part of the **Electric Barometer Research Series**, an evolving framework  
for readiness-centric forecasting, asymmetric-loss metrics, and operational analytics.

---

## Motivation

Traditional accuracy measures mask the difference between:

- A 10-unit *over-forecast* during slow hours  
- A 10-unit *under-forecast* during peak throughput

Operationally, these are not remotely equivalent.

CWSL formalizes this asymmetry and provides a metric that aligns evaluation with  
**actual service readiness**, not statistical aesthetics.

---

## Repository Structure

```yaml
eb-papers/
│
├── main.tex # Master LaTeX document
├── references.bib # Bibliography for the paper
│
├── sections/ # Ordered chapter-level LaTeX includes
│ ├── 000_frontmatter.tex
│ ├── 010_introduction.tex
│ ├── 020_related_work.tex
│ ├── 030_contributions.tex
│ ├── 040_operational_motivation.tex
│ ├── 050_cwsl_methodology.tex
│ ├── 060_illustrative_example.tex
│ ├── 070_managerial_implications.tex
│ ├── 080_applications_across_industries.tex
│ ├── 090_conclusion.tex
│ └── 100_future_research.tex
│
├── macros/ # Reusable LaTeX commands/macros
│ └── commands.tex
│
├── figures/ # TikZ diagrams and figure .tex includes
│ └── 040_asymmetry_cost_curve.tex
│
└── tables/ # Tables included via \input{}
└── 060_intervals_example_table.tex
```


---

## Intellectual Contribution

This paper establishes:

### **1. The CWSL Metric**
A penalty-weighted, demand-normalized performance measure that embeds explicit  
shortfall and overbuild cost parameters.

### **2. Diagnostic Readiness Metrics**
Including:
- No-Shortfall Level (NSL)  
- Hit Rate within Tolerance (HR@τ)  
- Underbuild Depth (UD)  
- Symmetric comparators (wMAPE)

### **3. A Conceptual Framework for Operational Asymmetry**
Grounded in high-throughput, high-penalty environments (e.g., QSR, supermarkets, call centers).

### **4. A Pathway Toward Readiness-Based Forecasting**
CWSL forms the backbone of the forthcoming **Electric Barometer** forecasting paradigm.

---

## Compilation

### **Overleaf**
This project is fully Overleaf-compatible.  
Simply open the project and click **Recompile**.

### **Local Compilation**
Requires a modern TeX distribution:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

---

## License

This paper is the foundation of a broader system of research and open-source tooling:

- **Electric Barometer (Core Framework)**
Forecast-readiness modeling, asymmetric loss, and demand-conditioning engines.

- **EB-Metrics**
A standardized library of readiness-based metrics (CWSL, CWLL, UD, NSL, etc.).

- **EB-Adapters**
Wrappers and adapters for XGBoost, CatBoost, LightGBM, Prophet, and custom models.

- **EB-Examples**
Tutorials, sample notebooks, and live use-cases in QSR, retail, and logistics.

---

This repository uses the **BSD 3-Clause License**, chosen for:

- Broad commercial permissiveness
- Academic reproducibility
- Maximum adoption potential