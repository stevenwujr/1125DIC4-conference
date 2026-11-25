## Why

The workspace needs a spec-driven OpenSpec workflow to author an academic conference paper in `ICEIB paper/main.txt` based on the cloned `1111` repository (DIC3 OpenSpec design and the Taiwan Housing Intelligence Agent proposal). Specifically, the paper must follow IEEE conference style for ICEIB (`https://www.iceib.asia/`) and strictly adhere to the `2020 A-Z SOP` academic writing structure (`1111/myplan/A2Z_outline_example.pdf`).

## What Changes

- Define formal OpenSpec specifications for the ICEIB IEEE conference paper structure, the A–Z writing SOP mapping, and scientific-integrity/data-grounding rules.
- Refactor `ICEIB paper/main.txt` from MDPI *Engineering Proceedings* style into IEEE conference style with the required sections: `Abstract` (plus `Index Terms`), `I. Introduction`, `II. Related Work`, `III. Proposed Design`, `IV. Experiment`, `V. Conclusion`, and `References`.
- Enforce full coverage of the A–Z SOP dimensions (`A–F`, `G–L`, `M–O`, `PA–PM`, `Q–V`, `W–Z`), including an illustrative walkthrough example (`PJ`), mathematical formulation (`PM`), and comparative summary table (`O`), while preserving verified Taichung City 115 Q3 feasibility figures (`10,638` raw / `9,152` residential candidate records) without fabricating unexecuted experimental results.

## Capabilities

### New Capabilities
- `ieee-iceib-paper-structure`: Defines the required IEEE conference manuscript sections, formatting conventions, `Index Terms`, and IEEE numbered reference style for ICEIB submission.
- `a2z-academic-writing-sop`: Maps every section of the manuscript to the 26 rhetorical checkpoints (`A–Z`, including `PA–PM`) from `A2Z_outline_example.pdf`.
- `research-integrity-and-data-grounding`: Enforces factual grounding against `1111/` source documents, requiring exact Taichung 115 Q3 inventory counts and explicit separation between completed data feasibility and pending experimental execution.

### Modified Capabilities
<!-- No existing specs in openspec/specs/ yet -->

## Impact

- Creates OpenSpec artifacts under `openspec/changes/iceib-ieee-paper/` and promotes approved specifications to `openspec/specs/`.
- Updates `ICEIB paper/main.txt` to conform to IEEE ICEIB conference style and the A–Z writing SOP.
