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

## Full research-grade implementations

This repository contains **minimal demonstrations** of each diagnostic.

Full research-grade implementations — including extended notebooks,
datasets, stress variants and documentation — are available here:

👉 Diagnostic Stack (CID-1 · LSD-1 · RSD-1)  
👉 https://hotza1.gumroad.com/l/arculy

## Philosophy

If a system can be learned too easily, something is leaking.
