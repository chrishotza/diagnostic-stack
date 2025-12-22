# Diagnostic Stack — Structural & Learnability Analysis

This repository provides **empirical diagnostic tools** to detect:

- hidden coupling between signals
- regime shifts in non-stationary systems
- learnability stress in ML pipelines

These tools are **diagnostic, not predictive**.

## Included diagnostics

- **CID-1** — Coupling / Independence Diagnostic  
- **LSD-1** — Learnability Stress Diagnostic  
- **RSD-1** — Regime Shift Diagnostic  

Each folder contains a **minimal reproducible demo**.

## Why this matters

Standard metrics often fail to detect:
- information leakage
- structural dependency
- silent regime transitions

These diagnostics are designed to fail loudly.

## Full research-grade versions

The complete notebooks, datasets and extended analyses are available here:

👉 **Gumroad – Diagnostic Stack (full version)**  
👉 *[(link)](https://hotza1.gumroad.com/l/arculy)*

## Philosophy

If a system can be learned too easily, something is leaking.
