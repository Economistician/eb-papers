# Cost-Weighted Service Loss (CWSL) — Long-Form Technical Paper  
**Electric Barometer Research Series**  
Author: **Kyle Corrie** (kcorrie@economistician.com)

![License: BSD-3](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)
[![Overleaf](https://img.shields.io/badge/Overleaf-Project-green?logo=overleaf)](https://www.o)
[![PDF](https://img.shields.io/badge/Paper-PDF-red)](https://github.com/Economistician/eb-papers/releases/latest)

---

## Overview

This repository contains the long-form technical paper introducing  
**Cost-Weighted Service Loss (CWSL)** — a demand-normalized, asymmetric forecast  
evaluation metric designed for high-frequency operational environments  
(e.g., QSR, retail, logistics).

CWSL generalizes wMAPE by incorporating explicit penalties for:

- **Shortfalls** (under-forecasting)  
- **Overbuild** (over-forecasting)  
- **Operational asymmetry** between the two  

The metric is designed to align forecast evaluation with *real operational cost*,  
not abstract statistical error.

This paper is part of the **Electric Barometer** ecosystem — a suite of tools,  
metrics, and modeling frameworks developed for modern operational forecasting.

---

## Repository Structure

```yaml
eb-papers/
│
├── main.tex # Master LaTeX document
├── references.bib # Bibliography for the paper
│
├── sections/ # Ordered section inputs for the paper
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
├── figures/ # TikZ figures or PDFs/images included in the paper
│ └── 040_asymmetry_cost_curve.tex
│
├── tables/ # Any formal table .tex includes
│ └── 060_intervals_example_table.tex
│
└── macros/ # Custom LaTeX commands
└── commands.tex
```

---

## Compilation

The paper is written in standard LaTeX and can be compiled using:

### **In Overleaf**
Click **Recompile**  
(Overleaf Git Integration is enabled — changes sync automatically.)

### **Locally (CLI)**
Requires:

- TeX Live 2022+  
- `natbib`  
- `tikz`  
- `booktabs`

Compile with:

```bash
pdflatex main.tex
bibtex main
pdflatex main.tex
pdflatex main.tex
```

---

## Purpose of This Paper

This long-form paper:

1. Introduces and formalizes the CWSL metric
2. Connects operational asymmetry to forecast evaluation
3. Derives diagnostic submetrics (NSL, UD, Hit Rate)
4. Demonstrates applied value through illustrative examples
5. Provides guidance for selecting penalty parameters
6. Shows cross-industry use cases
7. Establishes the foundation for the broader Electric Barometer framework

---

## License

This repository uses the **BSD 3-Clause License**, consistent with the Electric Barometer ecosystem.