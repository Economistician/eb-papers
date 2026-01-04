# Forecast Readiness Framework (FRF) – Paper

This directory contains the canonical manuscript for the **Forecast Readiness
Framework (FRF)**.

The FRF paper formalizes a readiness-oriented approach to forecast evaluation,
providing conceptual foundations, evaluative structure, and managerial framing
for determining when forecasting systems are appropriate for operational use.

---

## Purpose

The purpose of this paper is to define forecast readiness as a first-class
evaluation concept.

The manuscript introduces:
- Readiness as distinct from predictive accuracy
- The role of operational asymmetry in forecast evaluation
- A structured framework for governing forecast deployment decisions

---

## Relationship to Other Constructs

The FRF paper establishes the evaluative context in which other Electric
Barometer constructs are defined and interpreted.

In particular:
- Cost-Weighted Service Loss (CWSL) is introduced as an asymmetric loss measure
  consistent with readiness-oriented evaluation
- Derived diagnostics (e.g., NSL, UD, HR@τ, FRS) are interpreted relative to the
  readiness framing established here

This paper does not attempt to exhaustively define all derived metrics.

---

## Contents

The manuscript includes:
- Conceptual motivation and background
- Formal definition of the Forecast Readiness Framework
- Discussion of operational asymmetry and readiness
- Illustrative examples
- Managerial implications and limitations
- Directions for future research

---

## Build Instructions

To compile the FRF paper:

pdflatex main.tex
bibtex references
pdflatex main.tex