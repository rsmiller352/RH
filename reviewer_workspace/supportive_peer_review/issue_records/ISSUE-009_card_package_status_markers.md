# ISSUE-009 — Public card package carries stale uncertified-status markers and internal tooling references

**Severity: Level 4 conditional (submission risk if the cards accompany the submission; otherwise a publication-package defect outside the journal decision).** Classification: PUBLIC-EQ-CARD_MISMATCH.

## Exact locations
Card package (extracted_eq_cards/): 74/148 cards with §0 status language "certifies nothing" (52), "[DRAFT marker]… pending witness → verifier → drift → RSM gate" (45), "TRANSITIONAL" (1 — LEM_005_029); 84/148 naming internal tooling/process (promote_card.py, RSM gate, draft_eq_spine, D-/F-/TD-numbers, durable witness, SRC hashes). Load-bearing instances: THM_002_014 (t_base = 2π) and THM_003_013 (Cap = 9) both carry "certifies nothing" markers while classed MAIN_SPINE_AUTHORITATIVE by PACKAGE_MANIFEST.json. Additionally: BRIDGE_016_007's dependency header cites ROLEDEF_003_007 and THM_016_005, neither included in the 148-card package (dangling audit trail).

## Claim under review
Whether the package can serve its stated purpose — "complete formal support, detailed intermediate derivations, and public mathematical traceability" — for a journal reader.

## Context examined
Package README, PACKAGE_MANIFEST.json (selection rule, authority classes), MANUSCRIPT_CARD_REFERENCE_MAP.json, full reads of THM_016_001/BRIDGE_016_007 and claim-level reads of ten more cards, mechanical sweeps for status markers. Charitable reconstruction (**adopted for substance**): the markers are non-destructive historical snapshots from the drafting stage; package-level selection from the active resolution supersedes them; the mathematics beneath is complete and, where checked, correct; the SEC016 cards show the intended clean form ("PROMOTED-BY-GOVERNED-TRANSACTION", no draft markers).

## Why the charitable reading does not close the issue
The reader has no access to the supersession logic. The visible text of the central time-theorem card says "Certifies NOTHING — pending…"; a referee handed this as formal support will quote it. The package would then *damage* confidence exactly where it is meant to supply it. The two dangling dependencies compound this: a reader auditing the 409 Bridge's own dependency list finds two cards missing from the "complete" package.

## Reader consequence
If submitted as supplement: near-certain referee derision of the formal apparatus, with collateral damage to the manuscript's credibility. If published independently (e.g., repository/Zenodo): same effect on any diligent reader.

## Smallest sufficient repair
1. One mechanical pass over the 74 affected cards stripping §0 governance blocks to the SEC016 template (retain: statement, proof, dependencies, falsifiers; remove: draft markers, gate/pipeline vocabulary, tooling names, decision numbers). The typed content — which is the value — is untouched.
2. Add the two missing dependency cards to the package, or a README note explaining their exclusion and restating what BRIDGE_016_007 consumes from them.
3. Add the one-page reader guide (card anatomy, ID↔section mapping, λ/Λ and α/x conventions) recommended in the coherence review.
