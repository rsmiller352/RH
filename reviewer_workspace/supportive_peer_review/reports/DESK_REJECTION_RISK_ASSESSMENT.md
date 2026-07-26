# Desk-Rejection Risk Assessment

Perspective: the manuscript has just reached the editorial office of a serious foundational-physics journal. Risks classified NONE / LOW / MODERATE / HIGH / CRITICAL; every risk above LOW carries evidence, likely editorial interpretation, substance-vs-presentation typing, and smallest mitigation. No venue-specific requirements are invented; standards are broadly accepted professional physics norms.

| Area | Risk | Notes |
|---|---|---|
| Title and subtitle | LOW | Unconventional but sober; subtitle accurately states the contribution. The title term is unexplained in-body (see R6) but that is not an editorial-triage issue. |
| Abstract | **MODERATE** | R1 below. |
| Opening pages | **HIGH** | R2. |
| First presentation of the single axiom | LOW | §1.1 is precise and non-grandiose. |
| Claims of derivation from one axiom | **MODERATE** | R3. |
| Terminology density | **MODERATE** | R4. |
| Unfamiliar notation | LOW–MODERATE | Notation is defined at use; the α/x and Π₀ items are referee-stage, not desk-stage. |
| Excessive length | **MODERATE** | R5. |
| Insufficient section orientation | LOW | Within-section orientation is excellent; the missing *global* roadmap is part of R2. |
| Overclaiming | **NONE** | The paper systematically under-claims; scope paragraphs are exemplary. A genuine asset at triage. |
| Sensational wording | NONE | Absent. |
| Pseudoscientific appearance | **MODERATE** | R6. |
| Numerological appearance | **MODERATE** | R7. |
| Unexplained numerical coincidences | LOW | The dangerous coincidence (two 2/3s) is surfaced and disarmed by the paper itself (§10) — a model move. |
| Unclear calibration | NONE | Calibration logic is among the paper's cleanest features. |
| Connection to established physics | **HIGH** | R8. |
| Claims of replacing existing physics | NONE | Explicitly disclaimed. |
| Statement of scope | NONE | Exemplary. |
| Discussion of limitations | LOW | Present and honest; would improve further with the measured-comparison passage (CI-9). |
| Formatting irregularities | **MODERATE–HIGH** | R9. |
| Equation presentation | MODERATE | Part of R9 (no numbering); display quality itself is good. |
| References | **HIGH** | R10. |
| Conclusion language | LOW | Restrained and accurate. |

## Principal risks

**R1 — Abstract omissions (MODERATE; presentation).** No problem statement; the paper's strongest quantitative outcome (muon ratio inside CODATA uncertainty) never stated; only the Koide ppm appears. *Editorial interpretation:* "unclear contribution." *Mitigation:* the two added sentences in ABSTRACT_REVIEW's patch.

**R2 — No introduction (HIGH; presentation/structure).** The paper opens in foundational ontology; the physics target disappears until §12; no roadmap; no literature situating. *Editorial interpretation:* "philosophy manuscript misrouted to a physics journal" — plausibly fatal at triage despite the disciplined content. *Mitigation:* the 1.5–2.5 page introduction specified in INTRODUCTION_REVIEW (problem, strategy, roadmap + chain figure, title assembly, scope).

**R3 — Single-axiom derivation claim (MODERATE; substance-adjacent presentation).** Editors have seen many "everything from one axiom" manuscripts. This paper's protection is its own discipline (typed steps, falsifiers, honest caveats), but that protection lives *inside*; the outside (title page, abstract, opening) currently signals the risky genre. *Mitigation:* same as R1/R2 — the introduction's sober problem-first framing is what flips the genre signal; also one sentence in the introduction stating the paper's own definition of "forced" (per terminology ledger).

**R4 — Terminology density (MODERATE; presentation).** ~25 theory-specific terms; six in the abstract alone. *Mitigation:* abstract lightening (done in patch); optional one-page glossary table (the paper's own terminology is consistent enough to tabulate mechanically); the introduction absorbs much of the on-ramp cost.

**R5 — Length vs consumption (MODERATE; presentation/structure).** 56 pages; the mass result consumes §§1–4 + parts of 5–7 + 8's readouts + 10–15; the staircase/growth results (§5), full aperture machinery (§6), G-silence/no-go (§7.7–7.8), and G = 18π are program material not consumed by the headline result. *Editorial interpretation:* "two papers interleaved." *Mitigation options (author's choice):* (i) keep scope but add a roadmap sentence per unconsumed block stating its program role and non-use in the mass chain (cheapest, preserves the closure-first completeness claim); (ii) compress §§5–7 by ~30% and demote G = 18π to a remark. The reviewer recommends (i) plus the §3 G-sentence — the completeness of the layer stack is itself part of the paper's argument that nothing was smuggled.

**R6 — Pseudoscientific appearance (MODERATE; pure presentation).** Surface pattern-matches that trigger the filter: "observer" in the title with no in-body assembly; internal codenames (S02, C4, T3, P0) suggesting a private system; named-but-never-stated theorems; a "gravity-role value" G = 18π. Each has a one-line repair (leakage audit; observer audit; §3 review). *The content itself is the opposite of the pattern* — which is why these surface repairs are high-leverage.

**R7 — Numerological appearance (MODERATE; presentation).** 2π, √2, 2/3, 2/9, 206, 409 in one derivation invites the reflex. Protections already present: typed derivations for each value, the §10 disambiguation, Pell-certificate rigor. Remaining exposure: the middle-only screen (CI-5) — the one value-bearing step that is asserted rather than argued; and the undisclosed Koide-saturation identity (Koide audit) which, if a referee finds it first, reads as "the 2/3 was baked in." *Mitigation:* the CI-5 placement passage and the Koide-audit disclosure paragraph — both convert exposures into sharpened claims.

**R8 — Connection to established physics (HIGH; substance-adjacent presentation).** Two references; no engagement with the lepton-mass-relation literature (Koide's own later work, Foot's geometric interpretation, extensions), no contact with the Standard Model's actual lepton sector (Yukawa couplings, running masses — the paper's ratios are implicitly pole-mass-like and this is never discussed), no comparison table with measured values. *Editorial interpretation:* "authors unaware of the field." *Mitigations:* introduction's literature paragraphs (R2); the measured-comparison passage (CI-9); **one paragraph acknowledging the running-mass/pole-mass question and stating at which scale the derived ratios are claimed to apply** — this is the audit's one identified *scientific-scope* gap a competent referee will certainly raise: the muon/electron ratio is scheme-stable enough that the sub-ppm statement is meaningful, but the paper should say so itself. |

**R9 — Formatting (MODERATE–HIGH; presentation).** No numbered equations; no numbered theorems; no figures; no tables; verbal cross-references; no author block (possibly intentional). For a 56-page derivation paper this is a genuine referee-burden problem and reads as non-standard practice. *Mitigation:* number the display equations (mechanical); consider theorem environments for the ~12 named results; add the chain-diagram figure; add the comparison table.

**R10 — References (HIGH; presentation).** Two items. Even granting the paper's self-containment ethic, a foundational journal expects the work situated. *Mitigation:* ~10–15 citations concentrated in the new introduction and a short related-work paragraph; no change to the derivation's self-containment claims required.

## Overall desk-stage prognosis
As submitted: **substantial desk-rejection probability at a mainstream foundational journal — driven almost entirely by R2 + R10 + R9 (structure/apparatus), not by content.** The same manuscript with the introduction, references, equation numbering, comparison table, and leakage repairs would present as a disciplined, unusually honest unconventional-foundations paper — the kind that gets sent to referees. None of the high risks requires touching the derivation.
