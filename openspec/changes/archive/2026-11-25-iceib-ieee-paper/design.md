## Context

The project integrates two layers from `1111/`: (1) the domain-agnostic `DIC3` OpenSpec decision-support framework (`design.md`, `openspec/`) and (2) the concrete `Taiwan Housing Intelligence Agent` proposal (`myplan/01_Proposal_Document.pdf`, `myplan/README.md`, `myplan/房產AI提案評估.pdf`, `myplan/A2Z_outline_example.pdf`). An initial draft of `ICEIB paper/main.txt` used MDPI *Engineering Proceedings* headings; per instructor direction, the manuscript must be authored under OpenSpec using **IEEE conference style for ICEIB** and the **2020 A–Z SOP**.

## Goals / Non-Goals

**Goals:**
- Structure `ICEIB paper/main.txt` into IEEE ICEIB sections: `Abstract` (+ `Index Terms`), `I. Introduction`, `II. Related Work`, `III. Proposed Design`, `IV. Experiment`, `V. Conclusion`, and `References`.
- Explicitly satisfy every A–Z rhetorical checkpoint (`A–F`, `G–L`, `M–O`, `PA–PM`, `Q–V`, `W–Z`).
- Maintain strict academic integrity by reporting only verified Taichung 115 Q3 feasibility data while clearly marking live training/agent benchmarks as pending protocol execution.

**Non-Goals:**
- Modifying the cloned reference repository `1111/`.
- Fabricating experimental results (`MAE`, `RMSE`, `R²`, or agent benchmark scores) prior to running experiments.
- Compiling a binary `.docx` or `.pdf` file (output target is `ICEIB paper/main.txt`).

## Decisions

1. **IEEE Conference Style over MDPI Format**: Use Roman-numeral section headings (`I.`–`V.`), `Index Terms`, `Fig.` / `TABLE` IEEE captioning conventions, and IEEE reference formatting (`[N] Initials Lastname, "Title," ...`) to target the IEEE Xplore / EI Compendex track of ICEIB (`https://www.iceib.asia/`).
2. **A–Z SOP Subsection Mapping**: Organize subsections in `III. Proposed Design` (`PA–PM`) and `IV. Experiment` (`Q–V`) so reviewers and the instructor can trace each A–Z element directly, adding a concrete dual walkthrough (`PJ`) and formal mathematical predicate/budget formulation (`PM`).
3. **Strict Integrity Guardrail**: Report the `10,638` -> `9,152` Taichung City 115 Q3 inventory (`Conditional Go`) as the completed empirical baseline under `IV. Experiment`, while explicitly denoting live Layer 1/Layer 2 runs as pending execution before camera-ready submission.

## Risks / Trade-offs

- [Proposal-stage manuscript lacking live benchmark numbers] → Frame `IV. Experiment` transparently around the completed data feasibility audit, parameter tuning plan, and falsifiable hypotheses (`H1–H3`) with clear pre-camera-ready placeholders.
- [Incomplete bibliographic metadata in source proposal PDF] → Preserve exact verified authors/years/titles/venues in IEEE format and flag unverified volume/page/DOI fields for final pre-submission verification.
