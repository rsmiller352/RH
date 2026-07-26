# Public EQ-Card Coherence Review

Review of the 148-card package as reader-support artifacts, against the charter criteria.

## 1. Do the cards match the manuscript?
**Yes, everywhere checked.** All load-bearing equations cross-checked (load-bearing equation review, 30 items; spectral chain cards read in full) agree exactly with the manuscript in content and value. No card contradicts a manuscript claim; qualifications and non-claims are preserved and usually *stronger* on the card side (e.g., BRIDGE_016_007 §6 restates the post-muon-exposure caveat; THM_016_003 lists "No particle identity, laboratory datum, SI unit… occurs in this theorem").

## 2. Same notation?
Substantially, with documented diffs (symbol_audit/MANUSCRIPT_EQCARD_NOTATION_DIFF.md): systematic Λ (cards) vs λ (manuscript) for amplitudes; x vs α for the phase (mirrored by the manuscript's own internal split); card-side decorations (scr superscripts, RO-labels) consistently dropped by the manuscript — the right direction.

## 3. Same definitions, dependencies correct?
Yes where checked. Card dependency headers (publication_dependencies) match the manuscript's logical order; the package's MANUSCRIPT_CARD_REFERENCE_MAP is internally consistent (union = 148 = package count; per-section support sets plausible against content). One gap: **BRIDGE_016_007's own dependency list cites ROLEDEF_003_007 and THM_016_005 — neither is in the package** (not in the 148, not in the index). The map's selection rule ("union of support_card_ids in the manuscript traceability ledger") evidently differs from the union of card-level dependency headers, so two cards referenced *by an included card* are absent. For a reader auditing the 409 Bridge's stated dependencies, two edges dangle. Classified INSUFFICIENT_PUBLIC_SOURCE (bounded): the manuscript itself does not depend on the missing cards' content beyond what included cards restate, but the package's internal audit trail is not closed. **Repair: include the two cards or annotate the package README.**

## 4. Do they avoid internal workflow language?
**No — this is the package's principal defect.** Quantified findings (Phase 4):
- 74/148 cards carry stale status markers: "certifies nothing" (52), "[DRAFT marker] … pending witness → verifier → drift → RSM gate" (45), "TRANSITIONAL" (1).
- 84/148 reference internal tooling/process by name (promote_card.py, RSM gate, draft_eq_spine, D-/F-/TD-decision numbers, "durable witness", governance envelopes, SRC_* hashes).
- The load-bearing chain of the 409 Bridge (THM_002_014, THM_003_013, THM_005_009, THM_007_007/008) includes cards whose visible §0 text says "Certifies NOTHING — pending …" while the package manifest classes them MAIN_SPINE_AUTHORITATIVE.
- The SEC016 chain (THM_016_001/003/009, BRIDGE_016_007/008, LEM_016_006, ROLEDEF_016_004) is much cleaner: promoted-status footers, no draft markers — evidence the authors know what a public card should look like.

**Charitable reconstruction (adopted):** the markers are non-destructive historical snapshots; package-level selection supersedes them. **Residual problem (survives):** a referee handed this supplement will read "certifies nothing" on the time-theorem card and cannot know the marker is stale. The supplement would then *damage* credibility precisely where it is meant to strengthen confidence. If the cards are published as-is, this is a Level 4 (submission-risk) defect *of the supplement*; if the cards are not part of the submission, it is moot for the journal but remains a defect of the public package.

## 5. Obsolete terminology?
The amendment/supersession history embedded in card §0 blocks (e.g., AX_001_001's account of the old "I = 1" axiom being demoted to a theorem) is historically transparent but forces the reader through the archaeology. Content-level terminology is current and matches the manuscript.

## 6. Do they help a reader verify the formal chain?
**Strongly yes, once past the governance blocks.** The mathematical sections of the cards read in full are complete, careful, and independently checkable (explicit matrices, group tables, exact rational certificates, universal-property proofs, falsifier lists). The division of labor is right: bookkeeping identities, expanded derivations, and proof mechanics live in cards; the manuscript keeps narrative. The cards also contain the answers to several manuscript gaps (1/√2 provenance; extent-vs-winding for 2π; the "not 6" Cap exclusion) — which is the self-containment problem in mirror image.

## 7. Cards as substitute for exposition?
Per the charter: not acceptable — and mostly not attempted. The manuscript never cites the cards (no in-text apparatus), so it cannot lean on them explicitly; the three places it leans implicitly (1/√2; γ_Ψ origin; middle-placement) are exactly the self-containment findings.

## Recommendations (smallest sufficient)
1. **If the cards will accompany submission:** strip or clearly quarantine the §0 governance blocks (a mechanical pass: delete draft markers, decision-number references, tooling names; keep statements, proofs, dependencies, falsifiers). The SEC016 cards are the template.
2. Add the two missing dependency cards or a README note closing the audit trail.
3. Add a package-level reader guide (one page): what a card is, how IDs map to manuscript sections, the λ/Λ and α/x conventions.
4. In the manuscript, state once (end of introduction or a data-availability note) that a formal card supplement exists and what it contains — currently the paper never mentions its own supporting apparatus.
