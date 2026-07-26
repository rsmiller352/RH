# Section 2 — Relational Arithmetic: Formalizing the Relational Ledger

**Purpose.** Give the positive count-and-transfer arithmetic: holdings, transfer, conservation, pairwise balance (Law of Symmetry Conservation), the 2N theorem, persistent closure, the three-register threshold, and the base extents t_base = 2π, m_base = 1/(2π).

**What the reader has.** §1's axiom and admission rules. **What remains after.** All later machinery consumes exactly this arithmetic; the section's closing list is an accurate contract.

**Comprehension assessment.** High through §2.7. The structural-absence-vs-zero device (§2.1), transfer semantics (§2.2), and the balance/involution formalism (§2.4) are explicit and complete. The 2N theorem (§2.5) is followable. §2.6's single erasure rule (w·w̄ ≡ ε only) is stated with admirable precision ("installs no free-group reduction, no context erasure"). §2.7's threshold argument is compact but sound at the stated level.

**§2.8 is the section's one hard passage.** The Relational Lift ("the two-endedness of that relation is itself a second degree of freedom") and the jump to t_base = 2π carry the paper's only dimensional-style constant into existence in half a page. The supporting card (THM_002_014) contains a genuinely careful non-circularity analysis: 2π is the angular extent of a *static* closed object (total turning), never an assumed temporal rotation, with the extent (2nd DoF) separated from the winding count (1st DoF, = I). The manuscript's fences say what 2π is *not* (not circumference, not radius, no clock, no ruler) more fully than what it *is*. Since m = 1/(2π) is the sole coefficient of the eventual mass law, this is where a skeptical reader will first push hard.

**Strongest passages.** §2.2's inadmissible-transfer semantics ("Nothing changes. The ledger remains exactly as it was. There is no post-state."). §2.4's pairing formalism. The boundary/failure paragraph (§2.9) — the {exhibit X, and Y falls} list here is concrete and genuinely usable by a referee.

**Reader friction.** (1) §2.8 as above — the strongest available justification exists in the public card but only its conclusion appears in-text. (2) The sign-decomposition rule x ↦ (σ, |x|) introduces Σ_rel without definition (ledger U3; trivial). (3) "second degree of freedom, in the Section 1 sense" — Section 1 never uses the phrase "degree of freedom"; the backward reference dangles.

**Notation.** h, supp, ⪰, ι, mult all clean. ε for empty walk later collides benignly with ε₄ (§5).

**Transitions.** Excellent on both ends.

**Persuasive strengths.** Cancellation-as-theorem and reachability-implies-balance make the "no hidden structure" claim concrete.

**Credibility risks.** The 2π passage presented as assertion-plus-fences may read as the first "rabbit from a hat" to a referee — precisely because everything before it is so explicit. This is a presentation gap, not (on the card evidence) a derivational one.

**Verified issues.** Feeds candidate issue CI-2 (t_base justification thin in-text) — classified in Phase 9.

**Smallest improvements.**
1. **Add 2–4 sentences to §2.8** carrying the card's extent-vs-winding argument into the paper: the closure's *count* is I = 1 (first DoF); its *extent* is the total turning of one orientation-preserving cycle, which is 2π for any figure and any scale (hence metric-free); the two are different readings of the same completed closure. This is the single highest-value small repair in §§1–5.
2. Fix the dangling "in the Section 1 sense" backward reference.
3. Parenthetically define Σ_rel.
