# Underbuild Depth (UD) – Technical Note

This directory contains a technical note formalizing the **Underbuild Depth (UD)**
construct within the Electric Barometer evaluation framework.

---

## Purpose

The purpose of this technical note is to define and analyze Underbuild Depth (UD)
as a structural measure of underservice severity in operational forecasting
contexts.

This note exists to isolate the mathematical and conceptual properties of UD
from broader loss formulations and readiness frameworks.

---

## Relationship to Core Frameworks

Underbuild Depth (UD) is a derived construct within the Electric Barometer
ecosystem.

It is primarily used to:
- Support asymmetric loss formulations such as Cost-Weighted Service Loss (CWSL)
- Provide interpretable structure for underservice regimes
- Enable readiness- and policy-aware evaluation of forecast error

This note does not introduce a standalone evaluation framework.

---

## Scope and Non-Scope

**In scope:**
- Formal definition of Underbuild Depth
- Structural properties and interpretation
- Relationship to underservice severity and regimes

**Out of scope:**
- Full loss construction (see CWSL)
- Readiness governance (see FRF)
- Implementation or empirical validation

---

## Status and Maturity

This technical note is maintained as a formal supporting artifact.

Its contents may evolve as related loss formulations and readiness mechanisms
are refined.

---

## Contents

The technical note includes:
- Conceptual motivation for Underbuild Depth
- Formal definitions and notation
- Structural analysis and interpretation

Refer to the paper itself for detailed exposition.

---

## Build Instructions

To compile the technical note:

pdflatex main.tex
bibtex references
pdflatex main.tex