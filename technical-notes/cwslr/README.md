# Cost-Weighted Service Loss Ratio (CWSL-R) – Technical Note

This directory contains a technical note formalizing **CWSL-R**, an extension of
Cost-Weighted Service Loss (CWSL) focused on sensitivity, calibration, and
governance of asymmetric cost ratios.

CWSL-R examines how variation and uncertainty in the cost ratio
$R = c_u / c_o$ affect loss behavior, interpretation, and readiness-aware
evaluation.

---

## Purpose

The purpose of this technical note is to analyze the behavior of CWSL under
variation in the cost ratio parameter and to provide a structured treatment of
cost asymmetry sensitivity and calibration.

This note exists to formalize response surfaces, sensitivity regimes, and
governance considerations associated with selecting and interpreting cost
ratios in operational forecasting contexts.

---

## Relationship to Core Frameworks

CWSL-R is a derived construct within the Electric Barometer ecosystem.

It is primarily used to:
- Characterize sensitivity of CWSL to asymmetric cost ratios
- Analyze response surface behavior across under- and overbuild regimes
- Support principled calibration of cost ratios
- Enable governance and diagnostic interpretation of asymmetric loss evaluation

CWSL-R extends, but does not replace:
- Cost-Weighted Service Loss (CWSL)
- Readiness-oriented evaluation frameworks (FRF, FRS)

---

## Scope and Non-Scope

**In scope:**
- Response surface analysis for CWSL under varying cost ratios
- Sensitivity analysis and regime behavior
- Balance-based and diagnostic calibration approaches
- Entity-level heterogeneity in cost asymmetry
- Readiness-aware interpretation and governance considerations

**Out of scope:**
- Definition of base CWSL loss function (see CWSL)
- Binary reliability or threshold metrics (see NSL, HR@τ)
- Deployment governance criteria (see FRF)
- Implementation details or empirical estimation

---

## Status and Maturity

This technical note is maintained as a formal supporting artifact within the
Electric Barometer series.

Its contents may evolve as calibration strategies, governance practices, and
readiness evaluation frameworks are refined.

---

## Contents

The technical note includes:
- Operational motivation for cost ratio analysis
- Formal response surface construction
- Sensitivity and regime analysis
- Calibration and heterogeneity considerations
- Governance and diagnostic interpretation
- Limitations and relationship to readiness

Refer to the paper itself for detailed exposition.

---

## Build Instructions

To compile the technical note:

pdflatex main.tex
bibtex references
pdflatex main.tex