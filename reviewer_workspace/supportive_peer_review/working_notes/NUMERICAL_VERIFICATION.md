# Reviewer Numerical Spot-Check (independent computation)

Performed with 40-digit precision arithmetic (mpmath), using only the manuscript's displayed exact expressions. Purpose: verify that the manuscript's printed decimals follow from its own symbolic results. This is reviewer diligence, not a re-derivation of the theory.

**Inputs used (from manuscript §§12–15 only):**
α = 2/9; λ_min = 1 − cosα/√2 − (√6/2)sinα; λ_mid = 1 − cosα/√2 + (√6/2)sinα; λ_max = 1 + √2·cosα; s_409 = 409·sin(π/409)/π; M_e^std = 0.51099895069 MeV; Koide functional Q_K.

| Quantity | Manuscript displays | Reviewer computation | Match |
|---|---|---|---|
| (λ_mid/λ_min)² intrinsic | strictly between 206 and 207 | 206.77031597272938861… | ✓ (interval and floor = 206) |
| s_409 | 0 < s_409 < 1 | 0.99999016667036730378… | ✓ |
| r_μ = s_409·(λ_mid/λ_min)² | 206.768282732054172011291935636779… | 206.768282732054172011291935636779295… | ✓ all printed digits |
| r_τ = (λ_max/λ_min)² | 3477.472837104598532313001225522648… | 3477.472837104598532313001225522648344… | ✓ all printed digits |
| M_μ^out c² | 105.658375512052928326006945941653… MeV | 105.658375512052928326006945941653237… | ✓ all printed digits |
| M_τ^out c² | 1776.984970813427147785657684886757… MeV | 1776.984970813427147785657684886757351… | ✓ all printed digits |
| Q_K^out | 0.666667566724259522274262656024415… | 0.666667566724259522274262656024415409… | ✓ all printed digits |
| Δ_K | 9.00057592855607595989357748742…×10⁻⁷ | 9.000575928556075959893577487422981×10⁻⁷ | ✓ |
| Δ_K/(2/3) | 1.35008638928341139398403662311…×10⁻⁶ | 1.35008638928341139398403662311344×10⁻⁶ | ✓ |

**Reviewer reference facts not present in the manuscript** (used for the desk-rejection and persuasiveness analysis, not as inputs to any derivation check):

- CODATA 2022 measured m_μ/m_e = 206.768 2827(46). The derived r_μ exceeds this central value by +3.2×10⁻⁸ — i.e., the derived value lies well inside the experimental uncertainty band (±4.6×10⁻⁶).
- The derived M_τ = 1776.985 MeV compares with the current experimental τ mass ≈ 1776.93(9) MeV: about +0.05 MeV (≈0.6σ) above the central value, comfortably consistent.
- The manuscript itself never quotes these measured values or makes these comparisons (see FIRST_READING_NOTES.md, F11).

**Conclusion of spot-check:** every printed decimal in §§14–15 is exactly reproduced from the manuscript's own symbolic expressions. The displayed numerics contain no internal arithmetic errors at any printed digit.
