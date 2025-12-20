# Cost-Weighted Service Loss (CWSL) – Technical Note

This directory contains a technical note formalizing the **Cost-Weighted Service Loss (CWSL)**
metric within the Electric Barometer evaluation framework.

CWSL quantifies asymmetric operational loss arising from forecast error by
explicitly weighting underbuild and overbuild according to their relative
economic impact.

---

## Purpose

The purpose of this technical note is to define Cost-Weighted Service Loss (CWSL)
as an interpretable loss formulation that reflects the asymmetric consequences
of forecast error in operational settings.

This note exists to formalize CWSL as a normalized loss metric suitable for
readiness-aware evaluation and comparison of forecasting systems.

---

## Relationship to Core Frameworks

Cost-Weighted Service Loss (CWSL) is a core evaluative construct within the
Electric Barometer ecosystem.

It is primarily used to:
- Encode asymmetric penalties for underbuild and overbuild
- Translate forecast error into operationally meaningful loss
- Support readiness-oriented evaluation and comparison
- Serve as a foundational component for derived diagnostics such as FRS and CWSL-R

CWSL operates alongside, but does not replace:
- Governance and deployment criteria defined in FRF
- Binary and threshold-based reliability metrics (e.g., NSL, HR@τ)

---

## Scope and Non-Scope

**In scope:**
- Formal definition of Cost-Weighted Service Loss
- Interpretation as a normalized, asymmetric loss metric
- Structural properties and operational meaning
- Illustrative examples, use cases, and limitations

**Out of scope:**
- Sensitivity and calibration of cost ratios (see CWSL-R)
- Readiness governance and deployment decisions (see FRF)
- Implementation details or empirical estimation

---

## Status and Maturity

This technical note is maintained as a formal supporting artifact within the
Electric Barometer series.

Its contents may evolve as asymmetric cost modeling and readiness evaluation
practices are refined.

---

## Contents

The technical note includes:
- Conceptual overview and operational motivation for CWSL
- Formal loss definition and notation
- Structural properties and interpretation
- Illustrative examples and use cases
- Limitations and boundary conditions

Refer to the paper itself for detailed exposition.

---

## Build Instructions

To compile the technical note:

pdflatex main.tex
bibtex references
pdflatex main.tex