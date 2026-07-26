# Section 7 — Closure and Junction Contracts

**Purpose.** Close the §6 seam internally: completion-rate object, junction obligations, orientation-before-readout, tick↔closure correspondence and rate equality, service cost, the update/closure identity, the G-operation and G-silence, and the driven-dynamics no-go.

**Comprehension assessment.** Good, with two demanding passages. The obligations inventory (§7.2) is a genuinely helpful device — the reader knows what the section owes before it pays. The tick↔closure bijection and windowed rate equality (§7.4) are clear. The identity proof (§7.6) is the philosophical deep point: the two-step argument (no licensed role left for a second process; a role-identical "second relation" is duplicate naming under the axiom) is compact but complete on its own terms — the axiom is doing real work here and the reader can see it do it.

**Reader friction.** (1) §7.7's G-operation: "The residual is the typed T₃ remainder slot of the system account, consumed here only as a category." T₃ has no public definition (ledger U5); the sentence survives only by its own fence. The G-silence condition G|self-coupled = 0 with the 0-as-absence-marker gloss is fine, but "self-coupled" is not defined either — the reader infers "when the system's own account is fully paired." (2) The relationship between §7.7's G-role and §3's G-value is handled by declaration ("used here by role, not by value"); honest, but the reader may wonder why the same letter is kept if the value is not usable — one clause on the intended eventual reunification (or its deferral) would help. (3) The no-go theorem (§7.8) is clear and its scope statement exemplary.

**Strongest passages.** §7.3 (orientation cannot be recovered from continuous phase — "Two completions with the same magnitude but opposite facing can have the same continuous phase reading") — a precise, checkable claim that grounds the paper's discrete-first stance. §7.6's duplicate-naming argument. §7.8's "register-absence is at most transient under continued driving."

**Notation.** cost[γ], r_int, r_closure clean. ⊖ reused from §5 consistently.

**Transitions.** Both boundaries explicit.

**Persuasive strengths.** The section shows the axiom functioning as an *instrument* (in the identity proof) rather than as a slogan — probably the paper's best answer to "what does the single axiom actually do?"

**Credibility risks.** T₃ and "self-coupled" are the section's leakage/underdefinition exposures; both are one-sentence repairs.

**Verified issues.** Feeds CI-7 (T₃ leakage).

**Smallest improvements.**
1. Replace "the typed T₃ remainder slot" with a public description ("the system account's remainder slot," dropping the internal tag) or define T₃ in one sentence.
2. Define "self-coupled" in half a sentence at §7.7.
3. Optional: one clause on the role/value split's intended resolution for G.
