# CID-1 — Coupling / Independence Diagnostic

CID-1 is a **research-grade diagnostic tool** designed to test whether two signals that *appear independent* actually share **learnable structure**.

This tool does **not** test causality and does **not** perform prediction.
Its sole purpose is **structural diagnosis**.

---

## What CID tests

The core question CID answers is:

> Can information from signal B help a model learn signal A **better than chance**?

If the answer is **yes**, then independence is likely violated.

---

## Diagnostic principle

If two signals are truly independent:

- A simple model trained on signal B  
- **should not** learn anything meaningful about signal A  
- Accuracy should remain near random baseline (~0.5)

If accuracy **exceeds baseline**, this indicates:

- Hidden coupling  
- Shared latent structure  
- Information leakage  
- Regime-level dependence  

CID deliberately uses **low-capacity models** to avoid overfitting tricks.
If coupling exists, *even weak models should detect it*.

---

## What CID is NOT

- ❌ Not a causal inference tool  
- ❌ Not a forecasting model  
- ❌ Not a correlation test  
- ❌ Not a black-box deep learning system  

CID detects **learnable dependence**, nothing more — nothing less.

---

## Included in this folder

- `cid_demo.ipynb` — Minimal empirical demo  
- Example independent & coupled signals  
- Clear interpretation thresholds  

---

## Typical use cases

- Financial regime diagnostics  
- Market microstructure analysis  
- Signal leakage detection  
- Synthetic data validation  
- Stress-testing independence assumptions  

CID is especially useful **before** deploying predictive models.

---

## Interpretation guidelines

| Accuracy | Interpretation |
|--------|----------------|
| ~0.50  | Signals behave independently |
| >0.55  | Possible shared structure |
| >0.60  | Strong coupling signal |

⚠️ These thresholds are **diagnostic heuristics**, not hard guarantees.

---

## Relationship to the Diagnostic Stack

CID-1 is the **structural foundation** of the stack:

- CID → detects coupling  
- LSD → tests learnability under stress  
- RSD → detects regime shifts  

CID answers:  
**“Should these signals be treated as independent at all?”**

---

## Commercial version

The full research bundle, including extended notebooks and documentation, is available here:

👉 https://hotza1.gumroad.com

---

## License

Released under the MIT License for research and educational use.
