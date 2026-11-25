## Context

`ICEIB paper/main.txt` establishes a compilable `IEEEtran` LaTeX draft compliant with `ieee-iceib-paper-structure`, `a2z-academic-writing-sop`, and `research-integrity-and-data-grounding`. Acting as an OpenSpec reviewer, several stylistic, typographical, and redundancy improvements were identified:
1. Sentence-initial `Fig.~\ref{...}` in Section III violates the IEEE Editorial Style Manual (which requires spelling out `Figure` at the start of a sentence).
2. Informal SOP phrasing such as `"cure"` / `"cure rationale"` in Section III prose can be elevated to formal IEEE engineering register (`"remediation"`, `"mitigation strategy"`) while retaining `% [PC: Cure / Cause]` traceability comments.
3. Key descriptions of the architecture, `Conditional Go` audit, and pending-benchmark status repeat similar clauses across `Abstract`, `I. Introduction`, `IV. Experiment`, and `V. Conclusion`.
4. TikZ node clearance in `Fig. 1` and label placement in `Fig. 2` can be tightened for cleaner two-column rendering on Overleaf.

## Goals / Non-Goals

**Goals:**
- Produce `ICEIB paper/main-1.txt` as a peer-reviewed, proofread, academically polished, and paraphrased `IEEEtran` LaTeX manuscript.
- Preserve 100% of verified data figures, `[1]`–`[24]` citation ordering, and A–Z SOP alignment.

**Non-Goals:**
- Overwriting `ICEIB paper/main.txt` (preserved intact for side-by-side comparison).
- Altering empirical claims or adding unexecuted benchmark scores.

## Decisions

- **Preserve `% [A]`–`% [Z]` Comment Traceability**: Keep A–Z SOP annotations in LaTeX comments while polishing visible prose to publication-grade IEEE style.
- **TikZ Spacing Polish**: Increase vertical clearance between the dual-branch layer and `Evidence & Safety Gate` in `Fig. 1` (`2.35cm`) and refine the `Fail` branch label position in `Fig. 2`.

## Risks / Trade-offs

- [Over-paraphrasing altering technical precision] → Lock all formal symbols (`MAX_REACT_STEPS = 6`, `G(E_T)`, `SSR`, `SCA`) and dataset counts (`10,638`, `9,152`, `61.9\%`) via explicit verification checks.
