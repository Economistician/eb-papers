# No-Shortfall Level (NSL) – Technical Note

This directory contains a technical note formalizing the **No-Shortfall Level (NSL)**
construct within the Electric Barometer evaluation framework.

NSL is introduced as a **binary coverage metric** for assessing interval-level
forecast reliability with respect to underservice risk.

---

## Purpose

The purpose of this technical note is to define No-Shortfall Level (NSL) as a
binary indicator identifying whether a forecast interval avoids underservice
relative to an operational service requirement.

This note exists to formalize NSL as a reliability and coverage construct,
distinct from continuous loss or depth-based measures.

---

## Relationship to Core Frameworks

No-Shortfall Level (NSL) is a derived construct within the Electric Barometer
ecosystem.

It is primarily used to:
- Evaluate interval-level forecast reliability with respect to underservice
- Define coverage regimes in readiness-aware evaluation
- Complement severity-based constructs such as Underbuild Depth (UD)
- Support asymmetric evaluation frameworks including Cost-Weighted Service Loss (CWSL)

NSL does not measure magnitude of error or loss; it indicates whether a
shortfall occurs at all.

---

## Scope and Non-Scope

**In scope:**
- Binary definition of No-Shortfall Level
- Interpretation as an interval-level coverage metric
- Structural properties and contrasts with related measures
- Use cases for readiness and reliability assessment

**Out of scope:**
- Continuous loss magnitude (see CWSL)
- Shortfall severity or depth (see UD)
- Governance criteria for deployment readiness (see FRF)
- Implementation or empirical calibration

---

## Status and Maturity

This technical note is maintained as a formal supporting artifact within the
Electric Barometer series.

Its contents may evolve as interval forecasting practices and readiness-based
evaluation mechanisms are further refined.

---

## Contents

The technical note includes:
- Conceptual overview and motivation for NSL
- Formal binary definition and notation
- Operational interpretation and properties
- Illustrative examples and contrasts with related metrics
- Use cases and limitations

Refer to the paper itself for detailed exposition.

---

## Build Instructions

To compile the technical note:

pdflatex main.tex
bibtex references
pdflatex main.tex