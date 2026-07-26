# ISSUE-002 — Missing journal apparatus: introduction, literature base, numbering, figures/tables

**Severity: Level 4 (submission risk).** Structural; content-independent.

## Exact locations
Global: no introduction section (manuscript opens at §1 ontology; physics target absent from body until §12); references = 2 items (CODATA, Koide 1983); zero numbered equations; zero numbered theorem environments (named results invoked verbally — "the seam theorem" §4.1, "the native geometry top-invariant theorem" §4.2, "the Section 3 invariant theorem" §4.2, "the time-bridge checklist" §8.9); zero figures; zero tables (bookkeeping arrays excepted); no author/affiliation block (PDF metadata empty — possibly intentional anonymization; flagged for author attention only).

## Claim under review
Not a manuscript claim — an absence-of-apparatus finding. Verified mechanically (pdftotext scan for numbering patterns and reference list) and by full reading.

## Context examined
Whole manuscript (stages 1–3); the package (stage 4) confirms the cards carry the formal apparatus (statements, dependencies) that the paper's verbal cross-references gesture at — so the *content* for numbered results exists and is already public.

## Strongest favorable interpretation
Deliberate minimalism: the paper's self-containment ethic and its refusal to argue from authority extend to declining conventional scholarly furniture; the two references are the only two external inputs actually consumed (electron datum; Koide's relation), which is philosophically consistent.

## Why that interpretation is insufficient
Editorial triage does not read philosophies of citation; it reads signals. The combination (ontology-first opening + two references + no numbering + no figures + "observer" title) pattern-matches to the non-serious-submission profile *regardless* of the disciplined content — the precise failure mode the review charter directs attention to (sound substance, presentation-triggered rejection). Separately, verbal cross-reference materially raises referee labor in a 56-page derivation, and the absence of any comparison table or chain figure withholds the paper's two most legible artifacts.

## Reader consequence
High probability of desk rejection at a mainstream foundational venue before any referee sees §13.1's rigor (full analysis: reports/DESK_REJECTION_RISK_ASSESSMENT.md, risks R2, R9, R10).

## Smallest sufficient repair (package of five mechanical/structural items)
1. Add the 1.5–2.5 page Introduction specified in reports/INTRODUCTION_REVIEW.md (problem, strategy, roadmap + chain figure, title assembly, scope) — also discharges ISSUE-004's preferred placement.
2. Add ~10–15 references concentrated in that introduction (lepton mass relations and Koide literature; discrete/relational foundations; running vs pole mass source for the comparison passage).
3. Number displayed equations (mechanical LaTeX pass); optionally promote the ~12 named results to theorem environments, which also discharges leakage item M8.
4. One figure: the derivation-chain diagram (I = 1 → arithmetic → FCC/RD → Ω → spectrum → 206/409 → ratios → calibration → Koide, with section pointers).
5. One table: the typed measured-comparison table (with ISSUE-007's repair).
None of these touches the derivation; items 3–5 are largely mechanical.
