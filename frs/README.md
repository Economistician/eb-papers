# Forecast Readiness Score (FRS) – Technical Note

This directory contains a technical note formalizing the **Forecast Readiness Score (FRS)**
construct within the Electric Barometer evaluation framework.

FRS is introduced as a **composite diagnostic** summarizing both service protection and
cost discipline by combining **No-Shortfall Level (NSL)** and **Cost-Weighted Service Loss (CWSL)**.

---

## Purpose

The purpose of this technical note is to define the Forecast Readiness Score (FRS) as an
interpretable, readiness-oriented summary measure for operational forecasting systems.

This note exists to formalize FRS as a composite diagnostic that reflects:
- Reliability of meeting operational demand (via NSL)
- Asymmetric economic consequences of forecast error (via CWSL)

---

## Relationship to Core Frameworks

Forecast Readiness Score (FRS) is a derived construct within the Electric Barometer ecosystem.

It is primarily used to:
- Provide a single, interpretable score capturing readiness-relevant performance
- Integrate coverage-style reliability (NSL) with asymmetric cost (CWSL)
- Support readiness-aware evaluation and comparison of forecasting systems

FRS is defined in terms of, and therefore depends on:
- No-Shortfall Level (NSL)
- Cost-Weighted Service Loss (CWSL)

FRS complements, but does not replace, governance and deployment criteria defined in FRF.

---

## Scope and Non-Scope

**In scope:**
- Definition of Forecast Readiness Score as a composite diagnostic
- Interpretation of FRS as readiness-oriented evaluation
- Structural properties and operational meaning
- Illustrative examples, use cases, and limitations

**Out of scope:**
- Full definition and derivation of NSL (see NSL technical note)
- Full loss construction for CWSL (see CWSL technical note)
- Readiness governance and deployment criteria (see FRF)
- Implementation details or empirical calibration

---

## Status and Maturity

This technical note is maintained as a formal supporting artifact within the Electric Barometer series.

Its contents may evolve as the underlying components (NSL and CWSL) and readiness evaluation
regimes are refined.

---

## Contents

The technical note includes:
- Conceptual overview and motivation for FRS
- Formal definition and notation
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