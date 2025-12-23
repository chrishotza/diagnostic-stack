# LSD-1 — Learnability Stress Diagnostic

LSD-1 is a diagnostic tool designed to test how **learnability changes under stress**.

It does not predict outcomes.
It evaluates whether a system becomes easier or harder to learn
when exposed to noise, shocks, or regime pressure.

---

## Core question

> Does the learnability of a signal remain stable under stress,
> or does it collapse / inflate abnormally?

---

## Diagnostic principle

A system can appear stable under normal conditions,
yet break structurally when stressed.

LSD measures this by comparing:
- baseline learnability
- stressed learnability

using the **same simple model**.

If learnability changes significantly, structure is not robust.

---

## What this demo shows

- A baseline signal with stable structure
- The same signal under stress (noise injection)
- A simple classifier probing learnability
- A comparison of accuracy before vs after stress

---

## What LSD is NOT

- Not a forecasting model
- Not a stress test for portfolios
- Not a trading strategy
- Not a deep learning benchmark

This is a **structural diagnostic**, not an optimizer.

---

## Full version

The full LSD-1 toolkit includes:
- sliding window diagnostics
- multi-level stress injection
- regime-aware analysis

👉 Available in the commercial Diagnostic Stack.
