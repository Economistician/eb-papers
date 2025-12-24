# Limited-Time Offer Readiness (LTOR)

Limited-Time Offer Readiness (LTOR) is a research paper within the
Electric Barometer series that examines how production systems should
operate under forecast uncertainty induced by Limited-Time Offers (LTOs).

Rather than treating LTOs as a demand-forecasting problem, LTOR frames
promotional periods as planned sources of instability that degrade
forecast reliability and amplify asymmetric operational risk. The paper
proposes a readiness-centric approach to production management that
governs decision-making when predictive accuracy is known to be reduced.

---

## Role Within Electric Barometer

LTOR extends the Forecast Readiness Framework (FRF) to the specific
problem of promotional regime shifts.

It clarifies:

- Why LTOs should be treated as exogenous readiness shocks rather than
  demand uplift signals
- How the Readiness Adjustment Layer (RAL) mediates forecast trust under
  planned instability
- How asymmetry-aware evaluation (e.g., Cost-Weighted Service Loss and
  No-Shortfall Level) shapes safer intraday production behavior

LTOR complements core Electric Barometer constructs by demonstrating how
readiness, loss asymmetry, and governance principles apply in environments
where uncertainty is deliberate rather than incidental.

---

## Repository Structure

This directory is organized as follows:

- `main.tex`  
  The canonical LTOR research paper, including abstract, sections,
  figures, tables, and references.

- `sections/`  
  Individual LaTeX section files composing the paper.

- `figures/`  
  LaTeX-based figures illustrating readiness-centric production control
  and system architecture.

- `tables/`  
  Summary and comparative tables referenced in the manuscript.

- `macros/`  
  Shared notation and command definitions specific to the LTOR paper.

- `references.bib`  
  Bibliographic references cited in the paper.

---

## Scope

This directory contains the authoritative LTOR research paper and its
supporting artifacts.

The paper does not propose promotional demand forecasting models, nor
does it provide implementation code. Empirical studies, operational
deployments, and software components related to Electric Barometer are
maintained elsewhere in the ecosystem.

LTOR defines conceptual boundaries, architectural patterns, and
governance principles for managing production risk during planned
promotional instability.