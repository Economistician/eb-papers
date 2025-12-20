# Electric Barometer – Research Papers

[![License: BSD-3](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)](LICENSE)

This repository contains the formal research papers and technical notes
associated with the Electric Barometer forecasting evaluation framework.

Electric Barometer is a decision-oriented system for evaluating operational
forecasts under asymmetric cost, readiness constraints, and managerial
actionability. The work emphasizes when forecasts are fit for deployment,
not merely when they are statistically accurate.


## Core Frameworks

The research program is organized around a set of related but distinct
conceptual frameworks:

- Forecast Readiness Framework (FRF)  
  A governance and evaluation framework for determining when forecasts are
  operationally deployable.

- Cost-Weighted Service Loss (CWSL)  
  A loss formulation encoding asymmetric operational costs of over- and
  under-forecasting.

- Readiness Adjustment Layer (RAL)  
  A structural layer for adapting forecast outputs based on operational
  readiness signals.

- Derived Metrics and Constructs  
  Including NSL, UD, HR@τ, and related measures supporting readiness-based
  evaluation.


## Repository Structure

Each top-level directory corresponds to a named construct or framework
(e.g., FRF, CWSL, RAL).

Within each construct, papers are organized by artifact type:

- paper/  
  Canonical or journal-oriented manuscripts defining the framework.

- technical-notes/  
  Supporting technical analyses, derivations, sensitivity studies, and
  extensions.

- business-notes/  
  Practitioner- or executive-facing summaries focused on operational and
  managerial implications.


## Scope and Intent

This repository serves as the authoritative record of the Electric Barometer
research program.

It includes conceptual frameworks, formal loss constructions, and technical
extensions, but does not aim to provide end-user tutorials or implementation
guides. Code implementations and applied examples are maintained separately.


## Status and Maturity

Papers and notes within this repository vary in maturity, ranging from
conceptual framing to formalized technical analysis.

Each paper or note includes its own README describing scope, status, and
intended audience.


## Ownership and Contact

Electric Barometer is an independent research program.

For inquiries related to the research, collaboration, or licensing,
please contact:

Kyle Corrie
kcorrie@economistician.com