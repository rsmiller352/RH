# Internal-Language Leakage Audit
*(Scope amendment #1 — sweep of the manuscript and public EQ cards for internal workflow, tooling, repository, or process vocabulary.)*

## A. Manuscript findings

Mechanical sweep (S0x/C\d/T\d/P\d codenames, workflow verbs, tooling names, gate/audit vocabulary, decision numbers) plus full-text reading. The manuscript is largely clean — no D-numbers, no tooling names, no "harness/validator/witness/gate" workflow vocabulary, no AI or repository references. Findings:

| # | Term | Locations | What a reader sees | Severity | Smallest repair |
|---|---|---|---|---|---|
| M1 | "S02 book" / "S02 book layer" | §3 (1×), §8.6, §8.8 | An undefined label; the paper's own sections are 1–15 and no S-numbering exists in-text. Unresolvable. | **Level 3** (invites "internal system showing through" inference at two load-bearing passages — the c=3 reading and the active-m/m_base distinction) | Replace all three with "the Section 3 base book" (or "the base book") |
| M2 | "the typed T₃ remainder slot" | §7.7 | An internal account-slot tag never defined | Level 2–3 | "the system account's remainder slot" |
| M3 | "a P0 prediction" | §8.9–8.10 | An internal prediction-class code | Level 2–3 | "a measured prediction" (the sentence already says this in its own words) |
| M4 | "the lens-calibration identity" | §8.9, §8.10 | A named internal result the paper never states, cites, or uses — pure dangling reference | Level 2 | Delete the phrase (the surrounding non-claim list loses nothing) |
| M5 | "C4" (title of §10; "C4 invariant", "lower C4 carrier assignments") | §10 | Partially inferable (four-cell) but never expanded; the "lower C4 carrier assignments… lie outside the present derivation" sentence addresses an internal audience about objects the reader has never heard of | Level 2 | Expand once ("the four-cell (C4) reference-frame invariant"); replace the carrier-assignments sentence with "no further structure of the four-cell frame is used in this paper" |
| M6 | "promoted" as status adjective ("the promoted pointwise co-reading", §3; "promoted readout", §9.2, §9.3) | §3, §9 | Workflow status vocabulary ("promotion" is the card system's lifecycle verb) used as if it named a mathematical property | Level 2 | §3: delete the adjective; §9: "established"/"admitted" |
| M7 | "the value-free closure office" | §3 | An internal role name with no public definition | Level 2 (inside the already-dense G passage) | Define in half a sentence or rewrite the passage (see §3 review) |
| M8 | Named-but-never-stated theorems ("the seam theorem", "native geometry top-invariant theorem", "Section 3 invariant theorem", "the time-bridge checklist… the seventh item") | §4.1–4.2, §8.9 | References to a formal apparatus the paper withholds | Level 2 | Display the statements as numbered results, or paraphrase without names |
| M9 | "recorded" language around the two-face record: "The formal authority retains its internal identifier" | §11.0 | Explicit, *honest* acknowledgment of an internal system | Level 1 (this is the right pattern — disclosure without leakage; keep) | none |

**Not found in the manuscript (clean):** harness, validator, witness, verifier, drift, RSM, gate (in workflow sense), spine, card, repo/repository, AI/model/agent vocabulary, decision numbers, file paths, hashes. The pdftotext scan and the PDF spot-reads agree.

**Aggregate manuscript verdict:** nine findings, all with one-line repairs; three at Level 3 boundary because they sit in load-bearing passages (M1) or form a cluster (M3+M4 with M8's checklist item in §8.9–8.10 — the densest leakage in the paper). No Level 4: nothing exposes tooling, process, or AI involvement; the leakage pattern reads as spine-vocabulary residue, not workflow disclosure.

## B. EQ-card findings

Quantified in PUBLIC_EQ_CARD_COHERENCE_REVIEW.md §4 and Phase 4 notes: 74/148 cards with stale draft/pending/uncertified status markers ("certifies nothing" on 52, including load-bearing THM_002_014 and THM_003_013); 84/148 naming internal tooling (promote_card.py, RSM gate, draft_eq_spine, D-/F-/TD-numbers, durable witness, SRC hashes). **If the cards accompany the submission, this is Level 4 (submission risk) for the supplement**: a referee reading "Certifies NOTHING — pending witness → verifier → drift → RSM gate" on the central time theorem has been handed the means to dismiss the formal apparatus. If the cards are not submitted, card-side findings do not affect the journal decision but remain publication-package defects. The SEC016 cards demonstrate the achievable clean form.

## C. Recommended action order
1. Manuscript: apply M1–M7 (mechanical, ~30 minutes of editing); decide M8's policy (numbered results vs paraphrase) as part of the equation-numbering decision.
2. Cards (if to be published): one mechanical pass stripping §0 governance blocks to the SEC016 template; keep statements, proofs, dependencies, falsifiers.
3. Re-run this audit's grep set after edits (patterns preserved in working notes).
