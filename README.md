# Electric Barometer · Papers (`eb-papers`)

![License: BSD-3-Clause](https://img.shields.io/badge/License-BSD_3--Clause-blue.svg)
[![Build PDFs](https://github.com/Economistician/eb-papers/actions/workflows/latex.yml/badge.svg)](https://github.com/Economistician/eb-papers/actions/workflows/latex.yml)
[![Latest Release](https://img.shields.io/github/v/release/Economistician/eb-papers)](https://github.com/Economistician/eb-papers/releases)
[![Cite this repository](https://img.shields.io/badge/Cite-CFF-yellow.svg)](https://github.com/Economistician/eb-papers/blob/main/CITATION.cff)

A research series defining the Forecast Readiness Framework (FRF) for evaluating forecast performance in operational systems under asymmetric error cost.

---

## Overview

The Electric Barometer Papers repository is the authoritative research home of the Forecast Readiness Framework (FRF). It contains a structured series of formal papers and technical notes that define, motivate, and extend a unified approach to evaluating forecast performance in operational systems where forecast errors carry asymmetric and context-dependent costs.

Rather than treating forecasting accuracy as a purely statistical problem, the work in this repository focuses on forecast readiness: the degree to which a forecast supports effective operational decision-making under real-world constraints. The Forecast Readiness Framework formalizes this perspective by introducing cost-aware evaluation principles, readiness diagnostics, and supporting theoretical constructs designed for high-frequency, demand-driven environments.

The repository includes:

- **Framework papers** that establish the conceptual and methodological foundations of FRF
- **Metric definitions** such as Cost-Weighted Service Loss (CWSL) and Forecast Readiness Score (FRS)
- **Supporting diagnostics and adjustment layers** (e.g., RAL, NSL, UD, HR@τ)
- **Technical notes** that develop specific components, edge cases, and extensions

All documents are written as self-contained research artifacts and are compiled reproducibly via automated workflows. While the work is motivated by operational forecasting contexts (such as production and service systems), the framework and methods are intended to generalize to any setting where forecast errors translate asymmetrically into operational cost or risk.

---

## Role in the Electric Barometer Ecosystem

`eb-papers` defines the theoretical and methodological foundation of the Electric Barometer ecosystem. It is intentionally research-focused and contains no production code.

The papers and technical notes in `eb-papers` formally specify the concepts, metrics, and evaluation frameworks that are implemented operationally in companion repositories. In particular:

- Forecast Readiness Framework (FRF) is defined and motivated here
- Metrics such as Cost-Weighted Service Loss (CWSL) and Forecast Readiness Score (FRS) are introduced mathematically in this repository and implemented in `eb-metrics`
- Evaluation logic, aggregation, and orchestration are implemented in `eb-evaluation`
- Feature engineering and panel construction live in `eb-features`
- Model integration and interface normalization are handled in `eb-adapters`

This separation ensures that theoretical definitions remain stable, auditable, and citable, while implementation details can evolve independently in code-focused repositories. Readers interested in practical application should consult the relevant implementation repositories, while citations of conceptual definitions should reference the appropriate paper in this repository.

---

## Repository Structure

This repository is organized around **research artifacts**, not executable code. Each top-level directory corresponds to a formal paper or a set of closely related technical notes within the Forecast Readiness Framework (FRF).

At a high level, the structure follows a consistent pattern:

- **Framework papers**  
  Directories containing full-length papers that establish core concepts and unifying theory (e.g., the Forecast Readiness Framework itself).

- **Technical notes**  
  Focused documents that define individual metrics, diagnostics, or supporting constructs. These notes develop specific components of the framework in greater mathematical or operational detail.

- **Document substructure**  
  Within each paper or note:
  - `main.tex` serves as the compilation entry point
  - Section files are organized under `sections/`
  - Figures, tables, and bibliographic assets are colocated with the document

All documents are written to be self-contained and independently citable. Automated workflows compile each paper or note into versioned PDF artifacts, which are attached to tagged GitHub releases.

This structure is intentionally stable: theoretical definitions and methodological rationale live here, while executable implementations reside in companion repositories within the Electric Barometer ecosystem.

---

## How to Cite

If you use material from this repository, please cite it appropriately based on what you reference.

- **Framework-level concepts or the repository as a whole**  
  Cite the *Forecast Readiness Framework (FRF)* paper, which serves as the unifying reference for this research series.

- **Specific metrics, diagnostics, or technical constructs**  
  Cite the corresponding paper or technical note directly (e.g., CWSL, FRS, RAL).

Citation metadata for the repository is provided in [`CITATION.cff`](./CITATION.cff).  
Each paper is intended to be self-contained and citable as an independent research artifact.

When in doubt, cite the most specific paper that defines the concept you are using.

---

## License

BSD 3-Clause License.  
© 2025 Kyle Corrie.