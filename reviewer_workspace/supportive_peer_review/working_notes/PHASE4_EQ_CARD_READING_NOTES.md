# Phase 4 — EQ-Card Reading and Indexing Notes

**Package:** 148 cards, all labeled `MAIN_SPINE_AUTHORITATIVE`, selected mechanically as the union of `support_card_ids` over the release-facing manuscript traceability records (18 records: front matter, 15 main sections, conclusion, bibliography). Card-ID union verified = 148 = package count.

**Key structural facts established in this phase:**

1. **The manuscript contains no in-text EQ-card citations.** No card ID, no citation apparatus, no mention of the cards. The card-to-section linkage exists only in the package's `MANUSCRIPT_CARD_REFERENCE_MAP.json`. Consequence: the self-containment audit cannot proceed reference-by-reference from the manuscript side; it proceeds section-by-section using the map's support sets, asking whether the section's load-bearing content survives with the cards absent. It also means a journal reader receives no pointer from the paper to the formal supplement.
2. **Card folder numbering (SEC001–SEC016) is internal spine numbering, not manuscript section numbering.** The map's `publication_path` names align: manuscript §1 ← SEC01 record, … §15 ← SEC15 record. Missing folders SEC012/SEC015 simply mean no referenced card originates from those internal spine sections.
3. **Support-set sizes per manuscript section:** §1:25, §2:22, §3:20, §4:26, §5:36, §6:13, §7:29, §8:36, §9:5, §10:5, §11:6, §12:3, §13:7, §14:5, §15:2; abstract:11; conclusion:7.

**Cards read in full:** THM_016_001 (D3 descent/spectrum), BRIDGE_016_007 (409 readout). Cards read at claim level (§0–§2): THM_016_003, LEM_016_006, ROLEDEF_016_004, BRIDGE_016_008, THM_016_009, LEM_009_005, THM_002_014, THM_003_013, AX_001_001. All 148 titles indexed in `EQ_CARD_INDEX.md`.

## Findings relevant to open friction points (from FIRST_READING_NOTES)

- **F3 resolved by card, not by manuscript.** THM_016_001 §1 derives the operator coefficient 1/√2 from the two-active/one-idle coupling norm ‖k_e(o)‖ = √2 via the normalized radius u² + v² = 1/2 ("frozen radius"). The manuscript presents A_{σ,j} with the 1/√2 coefficients bare. Self-containment status: load-bearing provenance exists only in the card → candidate REQUIRED MANUSCRIPT ADDITION (smallest repair: one sentence tying 1/√2 to the coupling radius/edge invariant already derived in §4).
- **F4 partially resolved.** The card proves the cube-root list is complete and exact (§3) but the *warrant* for passing to cube roots (three-channel branch structure) is presented in manuscript §12.1 with one sentence. Candidate OPTIONAL IMPROVEMENT.
- **F5/F6 (middle-only screen).** BRIDGE_016_007 asserts and constructs middle-only placement ("The factor acts once, after quadratic-support formation, on the middle rank… never acts on an amplitude and never uses a fixed sector label") with falsifier 11 ("a fixed sector replaces the middle rank"), and cites source ranges ("corrected placement and particle-role discipline", SRC_000219) that are NOT included in the public package. Neither the manuscript nor the included cards give a reader-visible argument for why the two-face 206-support screen attaches to the *middle* rank and not the maximum rank. Candidate persuasiveness issue (Level 3) — the obvious skeptical question "why not screen the max rank too (or instead)?" is not answered in the public materials.
- **F1 (t_base = 2π).** THM_002_014 contains a complete derivation with an explicit non-circularity ruling (the 2π is the angular extent of a *static* closed object, not an assumed temporal rotation; extent = 2nd DoF vs winding/count = 1st DoF). The manuscript's §2.8 compresses this to assertion + fences. Candidate OPTIONAL IMPROVEMENT (one orientation sentence distinguishing extent-DoF from count-DoF would carry the card's key idea into the paper).
- **F2 (Cap = 9).** THM_003_013 gives the full argument: register-walks are rooted by construction; the only licensed erasure is exact retrace; hence three rooted records are distinct admitted objects; fairness forbids canonical root selection; non-erasure forbids unlicensed unrooted quotient; account = (root, position) pairs = 9, with explicit exclusion of the alternatives 3 and 6. The manuscript compresses this well but the "not 6" alternative is absent in-text. Candidate OPTIONAL IMPROVEMENT.

## Major new finding: stale internal status markers in the public cards

- **74 of 148 cards** carry draft/pending/uncertified status language in their §0 governance blocks: "certifies nothing" (52 cards), "[DRAFT marker] … pending witness → verifier → drift → RSM gate" (45 cards), "TRANSITIONAL" (1: LEM_005_029).
- **84 of 148 cards** reference internal workflow tooling by name (promote_card.py, RSM gate, draft_eq_spine, D-/F-/TD- decision numbers, "durable witness", governance envelopes).
- The load-bearing dependency chain of the 409 Bridge (THM_002_014, THM_003_013, THM_005_009, THM_007_007, THM_007_008) includes cards whose visible text says "Certifies NOTHING — pending …" even though the package manifest classes them MAIN_SPINE_AUTHORITATIVE.
- The SEC016 chain cards (THM_016_001/003/009, BRIDGE_016_007/008, LEM_016_006, ROLEDEF_016_004) are cleaner: they close with "PROMOTED-BY-GOVERNED-TRANSACTION" and carry no draft markers.
- **Charitable reconstruction:** the markers are historical snapshots retained non-destructively from drafting; the package-level selection (active resolution, authority class) supersedes them. **Residual problem:** a journal reader or referee handed these cards as the formal supplement will read "certifies nothing" on the central time-theorem card with no way to know the marker is stale. This survives as a card-side coherence finding (for PUBLIC_EQ_CARD_COHERENCE_REVIEW and the internal-language leakage audit), not a manuscript defect.

## Manuscript–card agreement observed so far

- All checked equations agree exactly between manuscript and cards (spectrum, floor bounds, Pell certificates, pushout cardinality, screen factor, three-entry report, Koide gauge cancellation).
- Notation is consistent where checked, with one systematic difference: cards write Λ_k for amplitudes where the manuscript §12 writes λ with reference indices and uses Λ nowhere; the manuscript's λ_0, λ_1, λ_2 correspond to the cards' Λ_0, Λ_1, Λ_2 with identical formulas. (For the notation diff report.)
- Card BRIDGE_016_007 uses fuller Taylor endpoints (exact rationals for sin, cos bounds) than the manuscript displays; manuscript states the bounds exist "through degree nine/eight" without printing them — an appropriate division of labor (machinery in cards).
- BRIDGE_016_007 §6 states the post-muon-exposure disclosure in nearly the same terms as the manuscript abstract — good qualification preservation.
