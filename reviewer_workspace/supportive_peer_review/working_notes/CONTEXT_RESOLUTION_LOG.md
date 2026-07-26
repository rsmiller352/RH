# Context Resolution Log

Every candidate concern raised during the review, with its final classification after the full context-completion protocol (local ¶ → section → whole manuscript → relevant EQ cards → strongest charitable reconstruction → threshold). Dismissed or downgraded items are logged so they are not rediscovered under different wording. Issue records exist only for surviving Level 3–5 items.

| ID | Candidate concern (canonical statement) | Locations | Context stages | Classification | Level | Resolution summary | Record |
|---|---|---|---|---|---|---|---|
| CI-1 | The 1/√2 coefficient of the spectral operators has no in-text provenance | §12.2 | 1–6 complete | READER-COMPREHENSION_RISK (self-containment REQUIRED) | **3** | Card THM_016_001 §1 derives it (coupling norm √2, radius 1/2); manuscript preamble lists the coupling among starting data but never connects; charitable reading (reader infers from η = √2) fails because the normalization step is not inferable | issue_records/ISSUE-003 |
| CI-2 | t_base = 2π justified in-text by fences + assertion; extent-vs-winding argument card-only | §2.8 | 1–6 | EDITORIAL_CLARIFICATION | 2 | Card THM_002_014 carries a complete non-circularity derivation; manuscript states the correct conclusion with correct fences; a reader can grant and proceed; 2–4 carried-over sentences recommended (§2 review, self-containment audit OPTIONAL-strong) | log only |
| CI-3 | G = 18π identification passage is compressed; "value-free closure office" and "promoted" undefined | §3 | 1–6 | EDITORIAL_CLARIFICATION (+ leakage M6/M7) | 2 | Accounting content recoverable by a careful reader; G unconsumed downstream so no derivational exposure; rewrite recommended | log only (leakage components in ISSUE-005) |
| CI-4 | Π₀ (zero subscript) in §12.3 undefined; typographically collides with Π_o while denoting a different projector | §12.3 | 1–6 (math verified: U_J = all-ones; Tr = 9 correct) | NOTATION_INCONSISTENCY | 2 | Mathematics correct; charitable reading (reader recomputes) succeeds but at real cost in the paper's central section; rename + half-sentence | log only (bundled into ISSUE-003's repair list) |
| CI-5 | Middle-only placement of the screen factor s_409 is asserted, not argued, in all public materials | §13.4; BRIDGE_016_007 | 1–6 | PERSUASIVENESS_RISK / submission risk | **4** | Card asserts placement + falsifier; cited placement-discipline source not in package; no public exclusion of the screen-the-max alternative; survives all charitable reconstructions | issue_records/ISSUE-001 |
| CI-6 | Title phrase "observer-rooted asymmetry" never assembled in the body | title; §8.3 | 1–6 | PERSUASIVENESS_RISK | **3** | All components exist (§8.3, §10.2, §12 rootedness); assembly absent; charter requires title be understandable from the paper | issue_records/ISSUE-004 |
| CI-7 | Internal codename cluster in public text (S02, T₃, P0, lens-calibration identity, C4 partial, "promoted", named-unstated theorems) | §§3, 7.7, 8.6–8.10, 10, 4.1–4.2 | 1–6 | PERSUASIVENESS_RISK (leakage) | **3** | Individually Level 2; as a cluster raises the private-system inference at triage; all one-line repairs | issue_records/ISSUE-005 |
| CI-8 | The constitutive identification (minimum support ↔ electron record types the triple as charged-lepton masses) is never stated as such | §14.1–14.2 | 1–6 | READER-COMPREHENSION_RISK | **3** | Ingredients distributed (§8.6, §14.2); "why leptons" question has no explicit answer; one-sentence repair | issue_records/ISSUE-006 |
| CI-9 | No measured muon/tau comparison anywhere; the paper's strongest empirical fact is invisible; comparison scale/scheme never stated | §14.3 | 1–6 | PERSUASIVENESS_RISK | **3** | Charitable reading (deliberate input-hygiene) accepted as motive, insufficient as outcome: §15 proves post-derivation comparison is admissible by doing one | issue_records/ISSUE-007 |
| CI-10 | Undisclosed structural fact: radius √2 ⇔ exact unscreened Koide saturation (phase-independent within positivity); ppm deviation is exactly the screen's footprint | §15; §4.2; §12.2 | 1–6 (reviewer-verified symbolically + 30-digit numerics) | PERSUASIVENESS_RISK | **3** | If a referee derives this first, "2/3 was built in" reading damages the validation claim; disclosed, it sharpens the paper | issue_records/ISSUE-008 |
| CI-11 | Missing journal apparatus: no introduction, two references, no numbered equations/theorems, no figures/tables | global | 1–6 | submission risk (structural) | **4** | Content-independent; drives most of the desk-rejection probability | issue_records/ISSUE-002 |
| CI-12 | α (§12) renamed x (§13.1) for the same phase | §12.2/§13.1 | 1–6 | NOTATION_INCONSISTENCY | 1–2 | One-line fix; card mirrors the split | log only |
| CI-13 | 74/148 public cards carry stale "certifies nothing"/draft markers; 84 name internal tooling; two dependency cards missing from package | card package | 1–6 | PUBLIC-EQ-CARD_MISMATCH | **4 (conditional on cards accompanying submission)** | Charitable reading (stale snapshots superseded by package manifest) adopted for substance; reader-facing defect survives | issue_records/ISSUE-009 |
| CI-14 | Mass-scheme/scale of the derived ratios never discussed (pole vs running) | §14 | 1–5 | EDITORIAL_CLARIFICATION | 2 | Latent until a measured comparison is added; folded into ISSUE-007's repair (one paragraph typing the comparison) | log only |
| CI-15 | §2 forbids sign algebra on σ; §12 exponentiates σ = ±1 | §2.2/§12.1 | 1–6 | RESOLVED_BY_CONTEXT (with residue) | 2 | §1.2's number-class licensing + §12's "carried orientation" make the rendering lawful; the reconciliation is real but unstated — one licensing sentence recommended (bundled in ISSUE-003 repair list) | log only |
| CI-16 | Two 2/3s numerology risk | §§10, 12, 15 | 1–3 | NO_ISSUE | — | The manuscript itself surfaces and separates them; exemplary | — |
| CI-17 | D = π/(3√2) resembles Kepler packing density | §4.4 | 1–2 | RESOLVED_BY_CONTEXT | — | Explicit disclaimer present at point of use | — |
| CI-18 | 206-reflexivity (middle ratio generates the count that corrects the middle ratio) | §13 | 1–6 | RESOLVED_BY_CONTEXT (residue: optional defusing sentence) | 1 | Construction well-founded: intrinsic ratio exists first, screen consumes the floor count, recovery divides out s_409; appearance-level only | log only |
| CI-19 | Package README manuscript-hash differs from supplied PDF hash | intake | 1–2 | RESOLVED_BY_CONTEXT | — | Hash refers to manuscript source (MANUSCRIPT.md per package manifest), not the rendered PDF; recorded at intake | — |
| CI-20 | Abstract omissions (problem statement; outcome statement) | abstract | 1–6 | PERSUASIVENESS_RISK | 2–3 | Covered within ISSUE-002's structural repair set + ABSTRACT_REVIEW patch; not separately recorded | see ISSUE-002 |

**No candidate reached Level 5 (significant scientific concern).** No direct inconsistency, visible non-sequitur, type break, circular definition, empirical leak into a prediction, dimensional fault, or manuscript↔card conflict survived the protocol. Reopened items: none.

## Round 2 outcomes (revision re-evaluation, 2026-07-26)

| ID | R2 outcome |
|---|---|
| CI-1/ISSUE-003 | **RESOLVED** (rooted-radius subsection; Π_sym; θ_o unification; σ licensing) |
| CI-2 | unchanged (still recommended, Level 2) |
| CI-4 | **RESOLVED** (Π_sym) |
| CI-5/ISSUE-001 | **substantially resolved** (§13.5 betweenness argument + figure); residuals R2-a…d at Level 2 |
| CI-6/ISSUE-004 | **RESOLVED** (bold definition in introduction; §13.5 operative statement) — R2-c wording alignment pending |
| CI-7/ISSUE-005 | **mostly resolved** (S02/T₃/P0/lens-calibration/checklist removed; §8 rewritten); residual: "promoted" ×7, "closure office", "carrier assignments", §4 theorem names |
| CI-8/ISSUE-006 | **not addressed** (recommendation stands) |
| CI-9/ISSUE-007 | **muon comparison resolved exemplarily** (0.0069683σ, propagated uncertainties); **tau comparison still absent** |
| CI-10/ISSUE-008 | **RESOLVED** (eq:koide-unscreened; exact saturation + screened fingerprint) |
| CI-11/ISSUE-002 | **largely resolved** (introduction, figures, author block, declarations, key-equation labels); **references still 3 items — largest residual desk risk** |
| CI-12 | **RESOLVED** (x := θ_o) |
| CI-13/ISSUE-009 | **addressed by scope decision** (authority archive declared non-journal-facing; clean supplement projections shipped) |
| CI-14 | still open pending tau comparison (fold into that repair) |
| CI-15 | **RESOLVED** (§6 licensing sentence) |
| New R2-a…d | ancestry-chain grounding; tied-pair restriction clause; introduction/figure wording tension; the 4m = 2/π aside — all Level 2, recorded in REEVALUATION_ROUND_2_REPORT.md |

**Round 2 verdict: READY_AFTER_MINOR_REVISION.**
