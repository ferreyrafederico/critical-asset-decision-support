# Simple Quantitative Model

## 1. Objective

To economically quantify the alternatives defined in Step 2 (02_decision.md)
using a static expected value model.

This model does not yet include temporal dynamics or advanced simulations.

---

## 2. Economic Assumptions (Simulated and Realistic)

For this exercise, the following estimated values are considered:

- Economic value of in-process batch: USD 480,000
- Preventive maintenance cost (planned shutdown): USD 35,000
- Additional cost of unplanned shutdown (logistics, restart, overtime): USD 60,000
- Estimated reputational cost in case of total batch loss: USD 80,000

Total cost if failure occurs during the cycle:
480,000 + 60,000 + 80,000 = USD 620,000

---

## 3. Uncertain Variable

Define:

P = Estimated probability of component failure during the current cycle.

For this simplified model, an initial estimate is used:

P = 8% (0.08)

This probability is based on historical records and preliminary technical assessment.

---

## 4. Economic Evaluation of Alternatives

### Alternative A1 — Preventive Interruption

Certain cost:
USD 35,000

Expected value:
-35,000

---

### Alternative A2 — Continue Operation

If NO failure occurs:
Full batch value retained.

If failure occurs:
Estimated total loss: USD 620,000

Expected value:

EV = (0.08 × -620,000) + (0.92 × 0)

EV = -49,600 USD

---

## 5. Initial Comparison

| Alternative | Expected Value |
|-------------|---------------|
| A1 - Preventive Maintenance | -35,000 USD |
| A2 - Continue Operation | -49,600 USD |

From a purely static economic perspective:

Preventive maintenance presents lower expected loss.

---

## 6. Model Limitations

- Does not consider time-dependent increase in failure probability
- Does not incorporate scenario distributions
- Does not evaluate dynamic intervention thresholds
- Does not include probability sensitivity analysis

These aspects will be addressed in the next step (04_dynamic_model).
