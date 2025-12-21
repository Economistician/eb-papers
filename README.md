# Electric Barometer – Research Papers

[![License: BSD-3](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](LICENSE)

This repository contains the formal research papers and technical notes
associated with the Electric Barometer forecasting evaluation framework.

Electric Barometer is a decision-oriented system for evaluating operational
forecasts under asymmetric cost, readiness constraints, and managerial
actionability. The work emphasizes when forecasts are fit for deployment,
not merely when they are statistically accurate.


## PDFs (Latest Release)

Download the latest Electric Barometer papers and technical notes here:

https://github.com/Economistician/eb-papers/releases/latest


## Core Frameworks and Metrics

The research program is organized around a set of related but distinct
conceptual frameworks and governed evaluation primitives:

- Forecast Readiness Framework (FRF)  
  A decision-oriented governance framework for determining whether forecasting
  systems are fit for operational deployment under asymmetric error cost.

- Cost-Weighted Service Loss (CWSL)  
  An asymmetric loss formulation measuring the effective fraction of operational
  throughput lost due to forecast–demand misalignment.

- Readiness Adjustment Layer (RAL)  
  A deterministic, post-forecast control layer that applies bounded adjustments
  to mitigate readiness risk without retraining forecasting models.

- Reliability and Severity Diagnostics  
  Including NSL (No-Shortfall Level), HR@τ (Hit Rate within Tolerance),
  Underbuild Depth (UD), and related constructs supporting readiness-based
  evaluation and governance.

- Sensitivity and Calibration Analyses  
  Technical notes addressing tolerance selection, cost-ratio calibration,
  response-surface analysis, and entity-level heterogeneity within the
  Forecast Readiness Framework.


## Repository Structure

Each top-level directory corresponds to a named construct, framework,
or technical note (e.g., FRF, CWSL, HR@τ).

Within each construct, artifacts are organized by type:

- paper/  
  Canonical or journal-oriented manuscripts defining core frameworks.

- technical-notes/  
  Supporting technical analyses, derivations, sensitivity studies, calibration
  procedures, and governance extensions.

- business-notes/  
  Practitioner- or executive-facing summaries focused on operational and
  managerial implications.


## Scope and Intent

This repository serves as the authoritative archival record of the
Electric Barometer research program.

It includes conceptual frameworks, formal loss constructions, diagnostic
metrics, and calibration methodologies, but does not aim to provide end-user
tutorials or implementation guides. Code implementations and applied examples
are maintained separately.


## Status and Maturity

Papers and notes within this repository vary in maturity, ranging from
conceptual framing to fully formalized technical analysis.

Each paper or technical note includes its own README describing scope,
assumptions, status, and intended audience.


## Ownership and Contact

Electric Barometer is an independent research program.

For inquiries related to the research, collaboration, or licensing,
please contact:

Kyle Corrie  
kcorrie@economistician.com