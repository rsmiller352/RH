# Section 5 — Runtime Accounting: Tick, Escapement, and Residual Growth

**Purpose.** Convert the static residual Ω into a running account: residual register, per-tick feed, escapements, the update rule, the {3,4} staircase, the long-run rate, and the first growth consequence (2→4 jump).

**Comprehension assessment.** High. The tick/escapement/cell triage at the section head is exactly the right prophylactic. The update rule's branch semantics preserve the §2 discipline visibly. The staircase equivalence (gaps ∈ {3,4} ⇔ 2√2 < π < 9√2/4) is a pleasing exact statement a reader can verify mentally. The recurrence argument ("no licensed terminal book… there is no last tick") is unusual but stated as an account-level necessity with the irrationality point correctly demoted ("irrationality does not make ticks recur" — a distinction most drafts would blur).

**Strongest passages.** §5.2's feed-admission articulation ("The feed… is an admission, not a transfer from another register. No source register exists and nothing moves, so the transfer-conservation law is not being bypassed") — this heads off a sharp internal-consistency objection at exactly the right moment. The N_tick glyph warning ("Despite the glyph, it counts completed unit-account crossings"). The first-jump result stated with its precise scope ("This is a first-jump result only").

**Reader friction.** (1) The four-cell {26,27} reading is mentioned as "fenced as a separate object" but the reader never learns what it is — a fence around an invisible object is mildly disorienting (the four-cell frame arrives in §10; a forward pointer would fix it). (2) The 2→4 jump uses "the exact inequality π > 15√2/7" without derivation context — checkable but abrupt. (3) k vs K vs x index roles (ledger note) are never tabulated.

**Notation.** S_res, ω_cell aliases handled by the explicit §5.2 identity display. ⊕/⊖ typed carefully.

**Transitions.** Good; the boundary list (§5.7) is comprehensive.

**Persuasive strengths.** The section shows the residual value doing real work (staircase, jump), which retroactively justifies §4's care with Ω.

**Credibility risks.** A referee may ask what the runtime layer contributes to the mass result (answer: the escapement/posting machinery that §§12–13 consume via ΔI = 1 and the completed-count cycle; but the staircase and growth results are program material). See the length/scope discussion in the desk-rejection report.

**Verified issues.** None at Level ≥3.

**Smallest improvements.**
1. Forward pointer at the {26,27} fence ("the four-cell pooled reading is introduced in §10").
2. One-line index legend (k: update rule; K: closed form; x: count argument) — cheap, removes real friction.
