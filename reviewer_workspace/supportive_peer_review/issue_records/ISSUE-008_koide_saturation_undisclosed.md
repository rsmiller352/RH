# ISSUE-008 — The exact Koide-saturation structure of the unscreened spectrum is undisclosed

**Severity: Level 3 (persuasiveness risk).** Classification: PERSUASIVENESS_RISK. (A reviewer-discovered structural fact; verified symbolically and numerically.)

## Exact location
§15 (the validation's framing); §4.2 (η = √2); §12.2 (the spectrum).

## The fact (reviewer-established, from the paper's own displays)
For λ_k = 1 + r·cos(θ + 2πk/3) with all three amplitudes positive, the Koide shape of the quadratic supports is Q_K(λ²) = (Σλ²)/(Σλ)² = (3 + (3/2)r²)/9 — **independent of θ**. Hence Q_K = 2/3 exactly ⇔ r² = 2. The paper's derived radius (η = √2, entering the operators as 1/√2) is therefore precisely the Koide-saturating value: the *unscreened* derived spectrum satisfies the Koide relation exactly, for every admissible phase, and the entire reported deviation Δ_K = 9.0006×10⁻⁷ is the exact footprint of the single screen factor s_409 on the middle support. (Numerically confirmed at 30 digits: unscreened Q = 2/3 exactly at θ = 2/9; screened Q − 2/3 = 9.0006×10⁻⁷, matching the manuscript's displayed value.)

## Context examined
§15 in full; §12.2's symmetric-sum context; card THM_016_001 §3 (which *displays* Σλ = 3, Σλ² = 6 — one division away from the identity — without drawing the Koide connection); LEM_009_005 (gauge cancellation only). Charitable reconstruction: the authors may regard the identity as obvious from the card's symmetric sums, or may have judged that stating it would look like claiming Koide as derived. Neither reading is stated anywhere; the manuscript presents the 1.35-ppm closeness as an unexplained-but-checked consistency.

## Why nondisclosure is a live risk
The identity is one line of algebra from the paper's own displays. A referee who finds it first can write: "the 2/3 agreement is automatic — the ansatz form plus the radius guarantees it; the 'validation' validates the ansatz family, not the derivation." That framing is *unfair* on the merits (the radius is derived from closure geometry with no Koide reference — independence survives, as the Koide audit confirms), but the paper, by not owning the identity, hands the framing to its critics. Conversely, disclosed, the fact is a *strengthening*: the derivation forces the Koide-saturating radius from first principles (a sharper claim than ppm-closeness), and the screen's 9.0×10⁻⁷ displacement becomes a definite, falsifiable fingerprint distinguishing this theory from exact-Koide theories.

## Reader consequence
As published: the validation reads as a surprising numerical closeness whose structural origin the reader may discover and then mistrust. Repaired: the validation's logic is fully visible and its claim sharper.

## Smallest sufficient repair
A short paragraph in §15.2 (3–5 sentences), e.g.: *"The closeness to 2/3 has a structural origin that should be stated. For the derived spectral form, the Koide shape of the unscreened quadratic supports equals (3 + (3/2)η²)/9 independently of the phase; the closure-forced edge invariant η = √2 therefore saturates the Koide benchmark exactly, before the finite screen acts. The derivation did not aim at this value: η is fixed in §4 by the transfer orbit, with no reference to the Koide relation. The reported deviation of ≈9.0×10⁻⁷ is then precisely the footprint of the screen factor s_409 on the middle support — a definite, computable displacement distinguishing this construction from an exact Koide identity."* (Optionally: one clause noting the measured masses' own Koide value and its uncertainty relative to this fingerprint.)
