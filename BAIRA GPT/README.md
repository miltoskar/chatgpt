# BAIRA GPT — Evidence-first Physics AI

**Developer:** Miltiadis Karazoupis  
**Public plugin name:** BAIRA GPT  
**Package identifier:** `baira-gpt`  
**Release channel:** scientific beta, public submission candidate  
**Software license:** MIT (BAIRA-covered source).

BAIRA GPT is a scientific research assistant designed to investigate real physical systems using evidence-first models, missing-variable identification, provenance-aware research, bounded simulations, Monte Carlo experimentation, and interactive scientific reporting.

## Core scientific method

BAIRA GPT first identifies the relevant physical processes, real operating conditions and missing variables. It searches available primary measurements through authorized ChatGPT tools, tests whether observations support the proposed model and reports uncertainty. A measured constitutive response takes priority over a classroom idealization when the data cover the actual regime. When suitable evidence is unavailable, idealized formulas may be used as **explicitly labeled fallbacks**, not as observed physical truth.

Simulations, synthetic inputs, hypotheses and inferred quantities must never be represented as independently measured observations. Outputs are **AI-generated scientific results** and require independent checking.

## Implemented workflows and limits

The package contains reusable ChatGPT skills and local Python code for defined simulation regimes, offline evidence-manifest verification, environmental audits, condition-matched model assessment, Monte Carlo, diagnostic checks and structured exports. Where an authorized ChatGPT runtime supplies file generation, BAIRA GPT can produce self-contained interactive HTML reports, plain text, PDF and JSON. Interactive replay uses recorded states; it does not simulate new physics within the browser.

A plugin skill does not automatically grant Python, web browsing, persistent agents, external sensing or an independent server. It is **not** a universal physical solver or a substitute for experiment.

## Independent public identity

This project is named **BAIRA GPT** (`baira-gpt`) and is **separate** from the existing private **BAIRA** (`baira`) plugin. The private plugin and private BAIRA GitHub repository are not changed.

The publicly redistributable package excludes the separately copyrighted Evidence Research skill. It retains a distinct MIT-covered evidence audit and public source-discovery guidance. No license for the separate protected component is implied.

## Distribution status

This repository folder contains the public project documentation, but **the ChatGPT plugin has not yet been submitted for review, approved or listed publicly**. Read [submission status](PUBLICATION_CHECKLIST.md) for verified next steps. This page does not claim a public install link.

[Support](SUPPORT.md) · [Release notes](RELEASE_NOTES.md) · [BAIRA GPT MIT License](LICENSE) · [Privacy policy draft](PRIVACY_POLICY_DRAFT.md) · [Terms draft](TERMS_DRAFT.md)
