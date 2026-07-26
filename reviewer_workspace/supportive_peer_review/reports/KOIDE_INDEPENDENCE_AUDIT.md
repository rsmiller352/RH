# Koide Independence Audit

**Question.** Does the subtitle's claim of "Independent Koide Validation" hold up on the public materials — i.e., is the Koide relation demonstrably downstream of the mass structure, with no forward influence?

**Method.** Full-text search and reading of every Koide-relevant passage in the manuscript (§15, abstract, conclusion) and cards (LEM_009_005, THM_016_009); upstream inspection of every quantity entering the ratios (phase 2/9, radius 1/√2, m = 1/(2π), rank ordering, 206, 409, s_409, electron scale) for any Koide dependence; verification of the arithmetic.

## Findings

### 1. Are the mass coefficients derived without using Koide as input?
**Yes, on all public evidence.** The chain 2/3 → 2/9 → spectrum → q = mλ² → ratios contains no reference to Koide at any point (manuscript §§10–13; cards THM_016_001/003, BRIDGE_016_007). The word "Koide" first occurs in the body at §15 (after two abstract/§14-boundary mentions of ordering). The functional 𝒬_K is defined only in §15.

### 2. Is the coefficient normalization selected to enforce Q = 2/3?
**No.** The normalization facts that determine Q's neighborhood are: the operator form 𝟏 + (1/√2)(ζP + ζ̄P⁻¹), whose symmetric sums give Σλ = 3, Σλ² = 6 (card THM_016_001 §3). The reviewer notes (as the paper does not) that these trace identities make Q_K(λ²) = 6/9 = **exactly** 2/3 for the unscreened quadratic supports — and this holds for *every* phase θ in the positivity window (all three amplitudes > 0, which contains θ = 2/9), since Σcos(θ+2πk/3) = 0 and Σcos²(θ+2πk/3) = 3/2 identically, so √(q_k) = λ_k sums to 3 regardless of θ. Verified numerically at 30 digits: unscreened Q = 2/3 exactly at θ = 2/9; screened Q = 2/3 + 9.0006×10⁻⁷. **This is the structural reason the derived shape lands ppm-close to 2/3: the unscreened spectrum satisfies the Koide identity exactly (phase-independently within positivity), and the entire ≈9×10⁻⁷ deviation is precisely the footprint of the single screen factor s_409 on the middle support.** The manuscript never states this. See "Assessment" below — it cuts both ways and should be disclosed.

### 3. Is the phase or ordering fitted using measured muon/tau masses?
**No** as a matter of the published derivation: the phase is 2/9 = (1/3)·(2/3) from the trace-forced aperture; ordering follows from exact inequalities; no measured value occurs upstream (occurrence audit: zero matches for any measured muon/tau digit string, "PDG", or non-electron CODATA quantity). **Disclosure honored:** the abstract and §14.3/BRIDGE_016_007 §6 state the 409 construction postdates muon exposure — discovery context, disclosed, distinct from derivational input.

### 4. Does the electron alone supply the scale?
**Yes** (§14.2; BRIDGE_016_008). And the scale cancels identically in 𝒬_K (§15.1; LEM_009_005) — so Koide validation is independent even of the one empirical input.

### 5. Is Koide computed only after the mass structure is complete?
**Yes.** §15.0: "The charged-lepton report is complete before this section begins." Construction order in the manuscript and card dependency lists (THM_016_009 depends on 016_003/007/008; LEM_009_005 depends only on §9/§14-layer cards) confirm no back-edge.

### 6. Does the manuscript explain the independence clearly enough for skeptical reading?
**Largely yes** — §15's enumeration of what would break independence (selecting 2/9, adjusting s_409, choosing 206/409, altering rank, fitting a ratio) is exactly the right form. Two gaps: (a) the benchmark's own empirical status (that measured lepton masses satisfy Q ≈ 2/3) is never stated, so a Koide-naive reader cannot see why the check is diagnostic; (b) the *structural* origin of the near-2/3 value (item 2 above: the unscreened spectrum satisfies Koide exactly for every phase; the deviation is precisely the screen's footprint) is absent.

## Assessment of the structural fact in item 2
This fact strengthens and sharpens the paper simultaneously:
- **Strengthens:** the near-agreement is not a coincidence to be marveled at; it is an algebraic consequence of the 1 + √2·cos form — i.e., of structure fixed before any measurement. "Koide-consistency" is thereby *guaranteed at the ~ppm level* by the derivation's shape, and the validation's real content is that the screen's perturbation is small and of definite size.
- **Sharpens (and must be disclosed):** a skeptic who discovers this identity (one line of algebra) could argue the Koide check is *weak* as validation — any theory producing a 1 + r·cos(θ + 2πk/3) spectrum (all amplitudes positive) with radius r = √2 passes it automatically at zero screen. The radius √2 is exactly the Koide-saturating value: Q_K(λ²) = (Σλ²)/(Σλ)² = (3 + (3/2)r²)/9 = 2/3 ⇔ r² = 2 (reviewer-verified symbolically and numerically at r = 1, √2, 2). So the honest sentence is: **the derived edge invariant η = √2 is equivalent to exact Koide saturation of the unscreened spectrum, phase-independently within the positivity window; the screen then shifts the shape by a definite 9.0×10⁻⁷.** The paper derives η = √2 from the transfer orbit (§4) with no Koide reference — the independence claim survives — but the subtitle's "validation" is better described as: the derivation *forces* the Koide-saturating radius from closure geometry, and the finite screen makes a definite ppm-level refinement. Stating this is both more honest and more interesting than the current presentation.

## Classification
- Independence of the derivation from Koide input: **CONFIRMED on public materials.**
- Presentation of independence: adequate; two Level 2–3 disclosure gaps (benchmark's empirical status; structural origin of the near-agreement, including the η² = 2 ⇔ exact-Koide equivalence). Recorded as candidate issue CI-10 for Phase 9.

**Smallest repairs.** (1) One sentence on the benchmark's empirical status. (2) A short paragraph (3–5 sentences) stating the exact-saturation identity and re-typing the validation accordingly ("the closure-forced radius √2 saturates the Koide shape identically in the phase; the 409 screen displaces the shape by a definite 9.0×10⁻⁷, and the measured masses are consistent with that displaced shape"). This converts the paper's most attackable soft spot into one of its sharpest claims.
