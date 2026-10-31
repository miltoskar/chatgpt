# BAIRA — Evidence-first Physics AI

**Developer:** Miltiadis Karazoupis  
**Release channel:** Scientific beta  
**ChatGPT plugin:** [BAIRA](https://chatgpt.com/plugins/plugins_6adf205d376c8191a0c22962fd0d15e0) (currently private; public submission is not yet approved).

BAIRA is an empirical-first scientific research assistant for physics investigation, numerical experimentation, bounded Monte Carlo simulation, nonlinear/stochastic heuristics, scientific provenance checks, and interactive scientific reporting.

## Core scientific policy

For a real physical system, BAIRA should first identify relevant processes, environmental conditions, measured parameters, and uncertainty. It should seek independently sourced measurements and condition-matched empirical models before falling back to idealized textbook laws. Missing values must be disclosed, not fabricated. Synthetic data and AI-generated scientific results are never labeled as observations.

The user must independently verify all calculations, cited sources, measurements, model assumptions, and conclusions. Passing software tests does not establish experimental truth.

## Capabilities and limits

- Evidence-first scientific investigation and source-provenance checks.
- Simulation and seeded Monte Carlo within supported implemented regimes.
- Advanced heuristic hypothesis generation and proposed discriminating experiments.
- Missing-variable inventory and measured-response prioritization where implemented.
- Standalone HTML research dashboards, text, JSON, PDF, and reproducibility exports when file execution is available.
- Recovery and integrity checks for supported local workflows.

**Limits:** Plugin installation does not confer a Python runtime, continuous sensing, independent experimental verification, or autonomous access to arbitrary tools. HTML export in ordinary ChatGPT requires suitable file-generation capabilities. Multi-agent SDK execution requires its own supported backend. No universal calibrated physical solver is claimed.

## Public availability

This GitHub page is public documentation. It does **not** mean that the ChatGPT plugin has been reviewed, approved, or publicly listed. The current private build remains private pending the separate ChatGPT submission process.

## License and third-party components

BAIRA MIT-covered software is © 2026 Miltiadis Karazoupis. See [LICENSE](LICENSE) for the full MIT terms. Separately licensed Evidence Research content is **not** relicensed here and is **not** distributed from this public documentation directory. This repository's root license is separate from this BAIRA directory's license.

[Support and responsible disclosure](SUPPORT.md) · [Release notes](RELEASE_NOTES.md) · [Publication readiness](PUBLICATION_CHECKLIST.md)
