## Why

After converting `ICEIB paper/main.txt` into compilable `IEEEtran` LaTeX, the manuscript requires an independent OpenSpec-driven peer-review pass focusing on proofreading, academic tone polishing, and cross-section paraphrasing to produce a refined companion version (`ICEIB paper/main-1.txt`) without altering verified data or violating IEEE/A–Z constraints.

## What Changes

- Use OpenSpec as a structured reviewer to audit `ICEIB paper/main.txt` for grammatical accuracy, IEEE stylistic conventions (e.g., spelling out `Figure` at sentence starts, compound modifier hyphenation, non-breaking spaces), formal academic register, and verbatim repetition across sections.
- Introduce capability spec `academic-review-polishing` governing proofreading, academic polishing, paraphrasing diversity, and strict factual invariance.
- Generate `ICEIB paper/main-1.txt` incorporating all reviewer refinements while preserving full `pdfLaTeX` Overleaf compilability, 2020 A–Z SOP coverage, and verified Taichung City 115 Q3 feasibility figures.

## Capabilities

### New Capabilities
- `academic-review-polishing`: Enforces IEEE academic register, grammar and typography proofreading, cross-section paraphrasing to eliminate verbatim repetition, and invariant preservation of empirical data and citations.

### Modified Capabilities
<!-- Existing specs in openspec/specs/ remain intact -->

## Impact

- Adds OpenSpec review change artifacts under `openspec/changes/ieee-paper-review-polish/`.
- Creates `ICEIB paper/main-1.txt` alongside `ICEIB paper/main.txt`.
