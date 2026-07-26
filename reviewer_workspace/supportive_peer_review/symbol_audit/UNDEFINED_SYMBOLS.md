# Undefined or Forward-Used Symbols

Symbols appearing in the manuscript before (or without) an in-text definition. Each entry records the charitable reading and whether it survives as a finding.

## U1 — The operator coefficient 1/√2 (§12.2) — undefined provenance, load-bearing
A_{σ,j} = 𝟏_V + (1/√2)ζP + (1/√2)ζ̄P⁻¹ is the object whose spectrum becomes the mass ratios. The coefficient 1/√2 is never derived, named, or motivated in the manuscript. The public card THM_016_001 §1 derives it exactly (coupling norm ‖k_e(o)‖ = √2 from the two-active/one-idle unit record; normalized radius u² + v² = 1/2). §12's preamble lists "its two-active/one-idle coupling" among the starting data, and §4.2 derived η = √2 as the edge invariant, so the ingredients are on the page — but the connecting sentence is not. **Status: survives — the single clearest self-containment gap (see PAPER_SELF_CONTAINMENT_AUDIT). Smallest repair: one sentence at the display.**

## U2 — Π₀ (§12.3) — undefined and typographically colliding
The zero-subscript projector in U_J = 3Π₀ is never defined; it is not the rank-two Π_o of §12.1–12.2 but the rank-one uniform (Fourier zero-mode) projector. Mathematics verified correct; symbol undefined and near-identical to Π_o. **Status: survives (see collision report X2). Smallest repair: rename + half-sentence.**

## U3 — Σ_rel (§2.2) — used once, never defined
"σ ∈ Σ_rel" — the label set is named and never specified. Charitable reading: obviously the set of orientation labels; the card DEF_002_002 defines it. **Status: minor (Level 1); a parenthetical "(the set of orientation labels)" suffices.**

## U4 — Forward use of the spectral apparatus in §10.4
Π_o, E₀, E₁, P, ν(·), 𝟏_V all appear in §10.4 (to state the projector value 2/3) before their definitions in §12.1. §10.4 supplies a partial local gloss ("the rooted two-active projector on the three-state carrier") and §10's purpose (disambiguating the two 2/3s) requires mentioning the object early. Charitable reading: deliberate preview; resolves at §12. Residue: a reader who checks §10.4's algebra at first encounter cannot, because P and ν are not yet defined. **Status: reader-friction only (Level 2); smallest repair: one forward pointer sentence in §10.4 ("defined precisely in §12; quoted here only to separate the two values").**

## U5 — Internal codenames used as if defined (S02, C4, T3, P0, lens-calibration identity)
- "S02 book" (§3 ¶"Read at the S02 book layer…", §8.6, §8.8): S02 is internal spine numbering for what the manuscript calls Section 3's base book. Never expanded in-text. A reader cannot resolve "S02" to anything in the paper — the manuscript's own sections are numbered 1–15 and S-labels are used nowhere else. **Survives (see INTERNAL_LANGUAGE_LEAKAGE_AUDIT).**
- "C4" (§10 title and body): reads as an internal tag; the four-cell context is inferable from §10.2 but "C4" is never expanded as "the four-cell invariant" in a definition sentence.
- "the typed T₃ remainder slot" (§7.7): T₃ names a slot in a system account that exists only in internal materials; nothing in the manuscript defines T₃. The sentence survives only because it is immediately fenced ("consumed here only as a category").
- "a P0 prediction" (§8.9–8.10): P0 is an internal prediction-class label; undefined in-text.
- "the lens-calibration identity" (§8.9–8.10): named as something *not* unlocked, never otherwise referenced; undefined in-text.
**Status: all survive as leakage findings; smallest repairs are per-item (expand, define, or delete).**

## U6 — "the seam theorem", "the native geometry top-invariant theorem", "the Section 3 invariant theorem" (§4)
Results invoked by name that have no displayed statement, number, or citation anywhere in the manuscript (the manuscript has no numbered theorems). The content is summarized where invoked, so the reader is not stranded, but the naming implies a formal apparatus the paper never exposes. **Status: reader-friction (Level 2); repair options: give the statements as displayed numbered results, or drop the theorem-names in favor of plain summaries.**

## U7 — frac(·) (§5.4)
Used in the closed form without definition; standard fractional-part function, typed correctly as external reading. **Status: no issue (conventional notation).**

## Systematic note
The manuscript has **no numbered equations and no numbered theorem environments**. Nothing is therefore formally citable within the paper, and all cross-references are verbal ("the Section 3 invariant theorem"). This is a formatting-level cause of several entries above; see DESK_REJECTION_RISK_ASSESSMENT.
