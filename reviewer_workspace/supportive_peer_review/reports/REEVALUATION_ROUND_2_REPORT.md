# Re-Evaluation Report — Revision 2 (Overleaf source package)

**Input:** `intake/ObserverRootedAsymmetryOverleaf_R2.zip`, SHA-256 `aa45baf84e151ec98518960a7efaefc42cbef40cb46cafb400af3af36d906b97`, 38 files: full LaTeX project (`main.tex`, introduction + 15 sections + conclusion + declarations, 5 TikZ figures with an accessibility alt-text file, `references.bib`) plus supplement ledgers (equation-label, notation/type, dependency-chain) and a mathematical-authority digest. Package-internal `FILE_HASHES.sha256` verified: zero mismatches. Extracted to `extracted_revision2/` inside the quarantine.

**Compile check:** the project compiles under pdfLaTeX + BibTeX exactly as its README instructs — **62 pages, zero LaTeX warnings, zero undefined references** — a real journal-facing improvement over review-by-source alone.

**Numerical check:** every new displayed number verifies at 40-digit precision: the muon comparison difference 3.2054172011×10⁻⁸ = 0.0069683 of CODATA's σ; the propagated uncertainties 105.658375512(33) and 1776.98497081(56) MeV; the screened Koide quotient with the √s₄₀₉ denominator reproducing 0.666667566724…

---

## Issue-by-issue outcomes

### ISSUE-001 — Middle-only screen placement *(was Level 4)* → **substantially resolved; residuals Level 2**
The revision adds §13.5 "Observer-Rooted Middle Placement": a betweenness argument (the lawful ancestry chain A ≺ B ≺ D has a unique interior element; a lawful observer readout is a bijective, betweenness-preserving map onto {min, mid, max}; hence ℛ(B) = mid, boxed as a labeled equation) plus a dedicated figure. This converts the placement from asserted to argued, and correctly notes that reversal exchanges endpoints while fixing the middle — the title concept doing real work. The introduction integrates it ("the regular-screen factor acts only on the rank selected by observer-rooted betweenness"). **Residual repairs (small):**
- **R2-a.** The ancestry chain A ≺ B ≺ D and lineage arrows (A→B, A→C, B→D; C, D co-present) are exactly §5.6's first-jump structure, but neither §13.5 nor the figure cites §5.6 — one cross-reference sentence grounds the chain in an already-proved result instead of introducing it as given.
- **R2-b.** The restriction from four cells {A,B,C,D} to the three-chain {A,B,D} needs one clause (C and D are co-present/tied, so any strict chain takes one representative of the tied pair; the choice is immaterial by the co-presence symmetry).
- **R2-c.** Internal tension: the introduction says the observer's "unique interior ancestry position determines which… rank receives the rendering," while the figure states, carefully, that the placement theorem "does not identify that cell with B." One of the two should be aligned (presumably the introduction's phrasing softened to "the interior position of the lawful ancestry chain, read by the observer, determines…").
- **R2-d.** The 4m = 2/π paragraph and figure note (disambiguating ancestry-D from geometric-D and displaying 4m = 2/π "at the completed four-cell location") answers a question no reader has asked and invites the numerological squint it is trying to prevent. Recommend cutting the 4m display entirely and keeping only the one-sentence D-type disambiguation.

### ISSUE-002 — Journal apparatus *(was Level 4)* → **largely resolved; one component open**
- Introduction: **added** — problem framing (charged-lepton hierarchy, PDG/CODATA context), the title term defined in bold at first use, contributions paragraph, explicit derivation-vs-calibration statement, post-exposure disclosure, and a section-by-section roadmap. Compact but effective.
- Figures: **added** — 5 TikZ figures (derivation architecture, FCC/RD geometry, spectral projections, betweenness placement, two-face 409 amalgamation) plus an ALT-text accessibility file. The architecture figure discharges the roadmap-diagram recommendation.
- Equation numbering: **partial** — twelve load-bearing equations now carry labels and in-text references (eq:rooted-radius, eq:action-phase, eq:quadratic-support, eq:screen-factor, eq:observer-middle, eq:muon-post-exposure, eq:koide-unscreened, eq:koide-screened, …); remaining displays are unnumbered equation* environments. Defensible referenced-equations style; the §4 named-but-unstated theorems ("seam theorem", "top-invariant theorem") remain unnumbered and unexhibited (leakage item M8, still open).
- Author block, affiliation, corresponding email, Declarations (funding, competing interests, data availability): **added**.
- References: **still open** — the bibliography grew from 2 to 3 (PDG 2024 added). No engagement with the Koide/mass-relation literature or relational/discrete-foundations literature. This is now the **largest single remaining desk-stage risk** (a triage editor seeing 3 references in a 62-page foundational paper).

### ISSUE-003 — 1/√2 provenance *(was Level 3)* → **resolved**
New §12 subsection "Rooted Radius and Operator Coefficient": coupling norm ‖k_e(o)‖² = 2, isometric transport, boxed rooted-radius identity (eq:rooted-radius), the unit-direction assembly u + iv = ζ/√2, and the closing sentence "The 1/√2 coefficient below is therefore the normalized rooted radius, not a fitted parameter." Exactly the repair requested. Bundled fixes also landed: Π₀ → **Π_sym** with an explicit definition and distinctness note ("distinct from the rooted occurrence projector Π_o") — collision X2 resolved; the phase symbol unified as **θ_o := Φ_o/3 = 2/9** in §12 with §13.1 explicitly setting "x := θ_o = 2/9" — collision X1 resolved; a σ-licensing sentence added in §6 ("only there are expressions such as exp(iσΦ_o) licensed") — X8 resolved. The cube-root warrant remains one sentence (minor, optional).

### ISSUE-004 — Title assembly *(was Level 3)* → **resolved**
The introduction defines the title in bold: "Observer-rooted asymmetry is the dependence of a lawful report on the observer's rooted ancestry and betweenness position, while the underlying unordered intrinsic spectrum remains presentation invariant." §13.5 states its operative form; the conclusion restates it. Subject only to the R2-c wording alignment above.

### ISSUE-005 — Internal codenames *(was Level 3)* → **mostly resolved**
Gone entirely: **S02, T₃ remainder slot, P0 prediction, lens-calibration identity, the time-bridge checklist** (§8 was rewritten in plain language, its energy content retyped as an "internal book-energy record"). Remaining: "promoted" as a status adjective (7 occurrences: §3 ×2, §6, §9 ×2, §11, §12, §15 — including "promoted response-chart notation" inside the new radius derivation and "composite of promoted identities" in §15); "the value-free closure office" (§3, unchanged G-passage); "lower C4 carrier assignments" (§10, unchanged sentence); the §4 named theorems. All one-line edits; downgraded to Level 2.

### ISSUE-006 — Constitutive identification *(was Level 3)* → **not addressed**
§14.1–14.2 are substantively unchanged on this point; no sentence types the electron anchoring as the constitutive identification of the support triple with the charged-lepton family. The recommendation stands as drafted in the issue record. (Note: the §8 restructuring removed the support-readout scaffolding, making this single sentence *more* valuable, not less.)

### ISSUE-007 — Measured comparison *(was Level 3)* → **muon resolved exemplarily; tau still absent**
New §14 subsection "Post-Exposure Muon Consistency Comparison": quotes CODATA's 206.7682827(46), displays the difference 3.2054…×10⁻⁸ (= 0.0069683 of the quoted σ), propagates the electron-standard uncertainty through both outputs (105.658375512(33), 1776.98497081(56) MeV), and types everything with exactly the right status language ("downstream comparison, not a construction equation… not a blind held-out prediction… no backward role"). This is the strongest single addition in the revision. **The tau comparison remains missing** — the favorable ≈0.6σ consistency of the τ output against the measured 1776.93(9) MeV is still nowhere stated, even though PDG 2024 is now cited. One short parallel display would complete the section.

### ISSUE-008 — Koide saturation *(was Level 3)* → **resolved, fully and elegantly**
New §15 structure: symmetric sums displayed; Q_int = (3 + (3/2)η²)/9 derived; the boxed equivalence **Q_int = 2/3 ⇔ η² = 2** (eq:koide-unscreened); exact 2/3 before screening, phase-independent within the positive-amplitude chamber; explicit non-circularity ("Koide's relation was not used to construct any of them"); then the screened quotient (eq:koide-screened) with the deviation identified as "the full algebraic departure… induced by the middle-rank finite-screen rendering." This adopts the audit's recommendation completely and converts the paper's softest claim into one of its sharpest. Still absent (minor): one sentence on the *empirical* status of the 2/3 benchmark for Koide-naive readers.

### ISSUE-009 — Card package *(conditional Level 4)* → **addressed by scope decision**
The cards are unchanged (not part of this upload), but `README_OVERLEAF.md` states the raw authority archive "is delivered separately and should not be uploaded as journal-facing manuscript content," and the package instead ships clean supplement projections (equation-label ledger, notation/type ledger, dependency chain, mathematical-authority digest). If that separation is maintained at submission, the conditional risk does not attach. The card-side cleanup recommendations remain for any public release of the cards themselves.

### Tier 2 items not taken up (still recommended, all small)
Abstract patch (unchanged abstract now also *understates the revision*: neither the 0.007σ muon consistency nor the exact unscreened Koide identity appears in it); t_base extent-vs-winding sentences (§2.8 unchanged; note m_base and the reciprocal-pair machinery were *removed* from §§2/8 — a clean simplification with no dangling references found); γ_Ψ origin sentence (§11 unchanged); Koide-benchmark empirical status.

---

## New observations in R2
1. The §8 restructuring (support readout, reciprocal pair, m_base, observer-scale reporting map removed; book-energy record retained with plain-language fences) is a net simplification that eliminates two prior audit concerns (m/m_base duality; §8.9–8.10 leakage cluster) with no dangling references detected.
2. The supplement ledgers (EQUATION_LABEL_LEDGER, NOTATION_AND_TYPE_LEDGER, DEPENDENCY_CHAIN) are clean, internally consistent with the source, and journal-appropriate in tone — the "clean projection" pattern the card package should eventually follow.
3. The muon agreement now stated (0.0069683σ) is strikingly close; the paper's honest post-exposure framing carries it, but the abstract's silence about it is now the biggest mismatch between what the paper achieves and what its front matter says.

## Updated verdict: **READY_AFTER_MINOR_REVISION**
Both former Level 4 blockers are resolved in substance (placement argued; apparatus present). Everything remaining is a local edit: the reference list (the one item with real desk-stage exposure), the abstract refresh, the tau comparison, the constitutive-identification sentence, the four placement residuals (R2-a…d), the γ_Ψ origin sentence, the benchmark-status sentence, and the residual codename sweep ("promoted", "closure office", "carrier assignments", §4 theorem names). Estimated effort: one to two focused days. No remaining item touches the derivation, and no new scientific concern was found in the revision — the new material (betweenness placement, saturation identity, uncertainty propagation) all verified correct.
