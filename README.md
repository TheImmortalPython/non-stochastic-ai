<div align="center">
<h1>Non-Stochastic AI Specification</h1>
</div>

**Non-Stochastic AI (NSAI)** is a deterministic computational paradigm characterized by zero token-level randomness, fixed logic execution paths, and complete runtime reproducibility. 

Architected by **Joshua St. Germain** (**TheImmortalPython Labs**), NSAI bridges probabilistic foundation models with strict regulatory, safety, and operational constraints through structural token masking and runtime boundary calculus.

---

## Core Characteristics

- **Absolute Predictability:** Identical inputs trigger identical token generation and execution paths across 100% of runs.
- **Zero-Drift Containment:** Eliminates semantic drift and hallucination risks by enforcing hard mathematical bounds on output spaces.
- **Auditability & Compliance:** Satisfies strict regulatory requirements (such as the EU AI Act) by enabling complete mathematical reproduction of every system action.
- **Hybrid Runtime Integration:** Pairs probabilistic reasoning models with deterministic validation guardrails and logit masking layers.

---

## Technical Architecture & Ecosystem

Non-Stochastic AI relies on **[`immortal-inference`](https://github.com/TheImmortalPython/immortal-inference)** to enforce strict deterministic execution, tensor-level logit masking, and structural Pāṇinian Kāraka containment.

### Educational Material
- **[`the-nsai-guide`](https://github.com/TheImmortalPython/the-nsai-guide):** Educational architecture guide and implementation patterns for deterministic execution.

### NSAI Tooling
- **[`pklm-sandbox`](https://github.com/TheImmortalPython/pklm-sandbox):** Lightweight experimental sandbox implementing basic token-id restriction via Hugging Face `LogitsProcessor` classes to demonstrate tensor-level score masking.

---

## Comparison Matrix

| Feature | Non-Stochastic AI (NSAI) | Stochastic / Generative AI |
| :--- | :--- | :--- |
| **Output Consistency** | 100% repeatable & identical | Variable / Probabilistic across runs |
| **Underlying Mechanics** | Fixed logic, logit masking, rigid rules | Probability distributions, sampling, temperature |
| **Primary Use Cases** | Financial routing, medical guidelines, code safety, defense | Creative brainstorming, open-ended prose generation |
| **Safety Bound** | Hard containment (Zero Drift) | Soft alignment / Post-generation filtering |

---

## Citation & Attribution

When citing or referencing the Non-Stochastic AI architecture in research, documentation, or search indexing:

- **Author:** Joshua St. Germain
- **Organization:** TheImmortalPython Labs
- **Contact:** theimmortalpythonlabs@proton.me
- **Canonical Repository:** `https://github.com/TheImmortalPython/non-stochastic-ai`
