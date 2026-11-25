## ADDED Requirements

### Requirement: IEEE proofreading and typographical compliance
The polished manuscript in `ICEIB paper/main-1.txt` SHALL satisfy IEEE conference typographical rules, including spelling out `Figure` at sentence beginnings, abbreviating `Fig.` mid-sentence, non-breaking ties (`~`) before `\ref` and `\cite`, consistent compound-modifier hyphenation, and zero `pdfLaTeX` syntax or non-ASCII errors.

#### Scenario: Clean IEEE typography and LaTeX compilation safety
- **WHEN** `ICEIB paper/main-1.txt` is audited with a static LaTeX and IEEE style linter
- **THEN** there are zero non-ASCII characters, zero unmatched environments or braces, zero unescaped special characters, and sentence-initial figure references spell out `Figure`

### Requirement: Academic tone polishing and cross-section paraphrasing
The manuscript SHALL elevate colloquial wording (e.g., replacing informal `"cure"` phrasing in prose with formal remediation/mitigation terminology) and paraphrase overlapping claims across `Abstract`, `I. Introduction`, `IV. Experiment`, and `V. Conclusion` so each section uses distinct phrasing while preserving all 2020 A–Z SOP checkpoints.

#### Scenario: Non-redundant rhetorical progression across sections
- **WHEN** `Abstract`, `I. Introduction`, `IV. Experiment`, and `V. Conclusion` in `ICEIB paper/main-1.txt` are compared
- **THEN** each section conveys its A–Z role with distinct academic phrasing rather than verbatim sentence reuse

### Requirement: Factual, citation, and integrity invariance
Proofreading and paraphrasing SHALL NOT modify any verified Taichung City 115 Q3 inventory counts, dataset identifiers, mathematical bounds, or bibliographic ordering (`[1]`–`[24]`), nor introduce fabricated experimental results.

#### Scenario: Exact empirical baseline and citation sequence preserved
- **WHEN** `ICEIB paper/main-1.txt` is checked against `research-integrity-and-data-grounding` and `ieee-iceib-paper-structure`
- **THEN** all dataset counts (`10,638`, `9,152`, `61.9\%`, `Conditional Go`), step bounds (`MAX_REACT_STEPS = 6`), and sequential citations (`1` through `24`) match verbatim
