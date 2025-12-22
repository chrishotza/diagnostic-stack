# RSD-1 — Regime Shift Diagnostic

RSD-1 is a diagnostic tool designed to detect **structural regime changes**
in time series data.

It does not predict future values.
It identifies whether the **underlying structure has already changed**.

---

## Core question

> Has the system entered a new regime, even if the signal looks smooth?

---

## Diagnostic principle

Many regime shifts do not appear as abrupt jumps.
Instead, structure changes gradually through:

- volatility shifts
- curvature changes
- gradient instability

RSD detects these transitions by tracking **local structural energy**
over time.

---

## What this demo shows

- A single time series
- A hidden regime change
- A structural diagnostic score
- Clear localization of the transition

---

## What RSD is NOT

- Not a forecasting model
- Not a trading signal
- Not a volatility estimator
- Not a causal inference tool

RSD provides **diagnostic insight**, not action recommendations.

---

## Interpretation

Spikes or sustained increases in the diagnostic score
indicate a likely regime transition.

---

## Full version

The full RSD-1 toolkit includes:
- sliding window diagnostics
- multi-scale structure probes
- regime persistence analysis

👉 Available in the commercial Diagnostic Stack.
