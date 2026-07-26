# Symbol Collision Report

Collisions found by the full-occurrence audit, ranked by reader impact. "Collision" = one glyph carrying more than one meaning, or one object carrying more than one glyph. Classification per ledger: CLEAR / AMBIG / CONFLICT.

## Conflicts (should be repaired before submission)

### X1 — α (§12) vs x (§13.1): one object, two symbols, adjacent sections
§12.2: "For the reference calculation set α = 2/9…" — the spectrum and all §12 displays use α. §13.1 opens: "With x = 2/9," and re-displays λ_min, λ_mid in terms of x. The same load-bearing phase carries two names across the section boundary where the paper's central computation happens, with no sentence connecting them. A careful reader will resolve it in seconds; a tired referee may wonder whether x is a new variable. The supporting card BRIDGE_016_007 also uses x, so the diff is manuscript-internal (§12 α vs §13 x), not manuscript-vs-card.
**Smallest repair:** in §13.1 write "With x = α = 2/9 (the spectral phase of §12)," or simply reuse α.

### X2 — Π_o vs Π₀ (§12.3): letter-o subscript vs zero subscript in one load-bearing display
§12.1/§12.2 consistently write Π_o (o = occurrence/rooted-cell label, matching A#_o, Φ_o, ρ_{o,σ}). §12.3 writes U_J = 𝟏_V + P + P⁻¹ = 3Π₀ with a zero subscript. The card THM_016_003 uses the letter-o form. Since U_J = 3Π₀ is false for Π_o = E_0 + E_1 — the correct identity is U_J = ∑_{r,p} E_rp whose Fourier form is 3·(projector onto the uniform vector), a *different* rank-one projector — the zero subscript is doing real work: Π₀ there must denote the rank-one projector onto the Fourier zero-mode, not the rank-two Π_o. The glyphs are near-identical in print. This is the one place in the manuscript where a typographic near-collision coincides with a genuine mathematical distinction. Verified: Tr(U_J†U_J) = 9 holds for U_J = all-ones matrix (‖U_J‖²_F = 9), consistent with the zero-mode reading, so the mathematics is right and only the notation is dangerous.
**Smallest repair:** rename the zero-mode projector (e.g., Π_unif or E^(0)) and add half a sentence identifying it.

## Ambiguities (documented or locally disambiguated; lower priority)

### X3 — τ: closure traversal (2π) vs lepton label
τ = 2π occupies §§3–8; M_τ, q_τ, r_τ occupy §§14–15. The uses never co-occur in a display, and the §14 use is a subscript, but the same italic glyph names both a central internal quantity and one of the three particles in the paper's title result. **Repair (optional):** a one-line footnote at §14.1 noting the reuse, or renaming the traversal label (heavier).

### X4 — E: book energy vs matrix units/projectors
E = 9/(2π) (§§3, 8.8) vs E₀, E₁ (§10.4, §12.1) and E_rp (§12.3). Subscripts disambiguate; fonts are identical. Because §8.8's "book energy" and §12's operators are both live near the paper's core, worth a footnote. **Repair (optional):** one clause at §12.3 ("the matrix units E_rp, unrelated to the book total E of §3").

### X5 — A# (bridge focusing parameter, §6.10) vs A#_o (intrinsic aperture value, §12.1)
Both use the # decoration; one is a free bridge-side parameter in (0,1], the other the forced intrinsic value 2/3. The subscript o is the only separator and the relationship (the §12 object is a one-pass instance of the aperture concept) is implied, not stated. **Repair (optional):** one sentence at §12.1 first use.

### X6 — I_bulk (bridge, §6.10) vs I_bulk,o = 1 (intrinsic, §12.1)
Same base symbol crossing the paper's most policed boundary (intrinsic vs bridge). The manuscript polices this boundary everywhere else; here the notation itself blurs it. **Repair (optional):** rename §12's to I_o or add a typing clause.

### X7 — the letter C
C_u / C_{1/2} (polytope, §4); C = {A,B,C} register positions (§3, via "let C denote the three retained register positions"); C = C_root = {r₀,r₁,r₂} (§§11.4, 13.2); C = {0,1,2} index set (§12.3); C₃ (cyclic structure); C4 (four-cell invariant tag). All 3-element C's are *related by construction* (the same three-ness descending the chain), which is exactly why accidental-vs-deliberate identity needs care: §13.2's "the subtraction term has independent provenance: 3 = |C|" works hard to separate C_root from the face counts, but nothing separates C_root notationally from §12.3's index C. **Repair (optional):** consistent subscripting (C_root everywhere in §13; C_idx or {0,1,2} inline in §12.3).

### X8 — σ as label (§2) vs σ as ±1 exponent (§12)
§2.2 is emphatic: "the labels are labels only: the theory attaches no sign algebra to them, no internal multiplication, addition, or parity action on σ." §12.1 then computes exp(iσ·2/3) with σ ∈ {+1,−1} — a multiplicative use of an orientation *realization*. The two are reconcilable (the §12 σ is the carried orientation rendered in the licensed complex-analytic downstream representation, per §1.2's number-class rule), but the manuscript never says so, and the §2 fence is strong enough that an attentive reader may flag the §12 use as a violation of the paper's own rule. **Repair:** one sentence at §12.1 ("the carried orientation is rendered here as the sign σ = ±1 in a licensed downstream representation; no sign algebra is attached to the underlying label").

### X9 — Overloaded small letters (r, u, s, k/K/x, R)
Each has 3–6 section-local meanings (see ledger). All are locally defined; none is load-bearing ambiguous. Standard for a long paper; no repair recommended beyond the specific items above.

### X10 — One value, many names: Ω family
Ω = Ω_geom = Ω_pack = Ω_cell^slot = ω_cell (§5.2 display). This is a *deliberate typed handoff* and the manuscript says so. It is listed here only because five names for one number is itself a reader cost; the §5.2 explanation is adequate.

## Manuscript-internal verdict
No collision found that breaks an argument. X1 and X2 are the two worth fixing before submission; X2 is the only one where notation could cause a technical misreading of a load-bearing display.
