## ADDED Requirements

### Requirement: Grounded Taichung City 115 Q3 feasibility inventory
All dataset metrics in the manuscript SHALL match the audited Taichung City Land Administration Bureau ROC Year 115 Q3 official CSV snapshot (`Dataset 103038`): `10,638` raw records (`32` fields) and `9,152` filtered residential candidates, explicitly labeled as a `Conditional Go` feasibility baseline.

#### Scenario: Exact inventory breakdown preserved
- **WHEN** data feasibility tables or prose report transaction categories and building types
- **THEN** transaction categories sum to `10,638` (`6,587 + 2,565 + 1,377 + 94 + 15`) and residential candidate building types sum to `9,152` (`5,933 + 1,553 + 1,461 + 205`)

### Requirement: Prohibition of fabricated experimental outcomes
The manuscript SHALL NOT invent model accuracy numbers, latency measurements, or benchmark win rates for unexecuted experiments, and SHALL distinguish completed feasibility findings from planned Layer 1 and Layer 2 evaluation protocols.

#### Scenario: Pending experiment status disclosed
- **WHEN** Section IV (`IV. Experiment`) reports results (`U`) and verification (`V`)
- **THEN** completed data-inventory findings are reported as observed while live ML valuation and ReAct-vs-workflow comparisons are explicitly stated as pending protocol items
