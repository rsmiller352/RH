# ISSUE-003 — The 1/√2 operator coefficient lacks in-text provenance

**Severity: Level 3 (persuasiveness risk / self-containment REQUIRED item).** Classification: READER-COMPREHENSION_RISK.

## Exact location
§12.2, the display A_{σ,j} = 𝟏_V + (1/√2)·ζ_{o,σ,j}·P + (1/√2)·ζ̄_{o,σ,j}·P⁻¹.

## Exact claim under review
The spectral operators — the objects whose eigenvalues become the mass-ratio amplitudes — carry off-diagonal coefficient 1/√2, presented without derivation, name, or reference.

## Context examined
- *Local/section:* §12 preamble ("The starting data are the rooted one-cell record, its two-active/one-idle coupling, the cyclic three-channel action, and the already established support coefficient m") — the coupling is listed but never used visibly; §12.1 derives phase but not radius; no other §12 passage touches the coefficient.
- *Manuscript:* §4.2 derives η = √2 as the edge invariant with the forward promise "the √2 that later appears… is this same edge invariant carried through" — but that sentence's enumerated destinations are the cell volume, filled share, and residual share (§4), not §12. No manuscript sentence connects η to the operator coefficient.
- *Cards:* THM_016_001 §1 derives it completely: the unit record's two-active/one-idle coupling k_e(o) = Q_o(1,1,0)ᵀ has norm √2; orthogonal transport preserves it; the positive ratio chart gives u² + v² = 1/2, i.e., off-diagonal radius 1/√2. Forced-step chain item 1: "Orthogonal norm preservation forces ‖z_A‖ = √2 and u² + v² = 1/2."
- *Charitable reconstruction:* an alert reader who remembers §4.2's promise might guess the coefficient is the edge invariant in normalized reciprocal form. The guess happens to be right, but the *normalization step* (why 1/√2 and not √2, and against what the radius is normalized) is not inferable from the manuscript.

## Why the charitable interpretation is insufficient
Everywhere else the paper's method is to type every constant's provenance at point of use; here, at the most load-bearing display in the paper, a constant appears bare. A referee applying the paper's own standard will flag it; a hostile one will call it a tuned parameter (it is not — the card's derivation is clean, and the Koide audit shows this radius is also exactly the Koide-saturating value, raising the stakes of leaving it unexplained).

## Reader consequence
The derivation chain's visibility breaks at exactly the point where the spectrum is born; the reader must either grant an unexplained constant or leave the paper.

## Smallest sufficient repair
One sentence at the display, e.g.: "The coefficient 1/√2 is not chosen: the unit record's two-active/one-idle coupling has norm √2 — the §4 edge invariant reappearing — and normalizing the one-pass response to the unit record fixes the off-diagonal radius at 1/√2 (the full calculation is the radius step of the spectral construction)." Bundled cheap repairs in the same section (from the symbol audit, all Level ≤2 but best done together): define/rename Π₀ in §12.3 (collision X2); one licensing sentence for the σ = ±1 rendering (CI-15); two-sentence cube-root warrant (F4); unify α/x with §13 (CI-12).
