# Life-Insurance-Pricing-Model
Dynamic actuarial model for pricing and reserving of a term life product using mortality assumptions and equivalence principle.

---

## Project Objectives
- To develop a dynamic actuarial pricing model for a term life insurance product using mortality and financial assumptions.
- To calculate gross premiums using the equivalence principle incorporating expenses and commission.
- To compute and compare prospective and retrospective reserves and validate model accuracy through reconciliation testing.
- To perform sensitivity analysis on key parameters (interest rate, entry age, term, sum assured) and assess impact on premiums and reserves.
- To structure actuarial model data and processes into modular input, calculation, and reporting components.

---

## Key Assumptions
- Product Type: Level Term Insurance.
- Mortality Basis: Standard mortality table applied without adjustments (no selection effects).
- Interest Rate: Constant annual effective interest rate (base case 6%).
- Premium Structure: Level annual premiums payable in advance throughout the policy term.
- Benefit Structure: Sum Assured payable at the end of the year of death.
- Expenses: Expenses are assumed to be constant over the years.
- Commission: Level percentage of premium (no renewal escalation).
- Inflation: Not modelled; all values expressed in nominal terms.
- Lapses: Ignored (policy assumed to remain in force until death or maturity).
- Bonuses: Not applicable (non-participating contract).


---

## Features
- Premium calculation (Equivalence Principle)
- Prospective & Retrospective reserves
- Reconciliation validation
- Sensitivity analysis (interest rate stress)
- Structured input-output dashboard

---

## Tools Used
- Microsoft Excel
- Mortality Table Assumptions
- Financial Mathematics (Time Value of Money)

---

## Model Validation
Reconciliation error maintained within tolerance threshold.
