# Public Derivation Dependency Map

Constructed from the manuscript and public EQ cards alone. Purpose: determine whether the public paper exposes enough of the chain from I = 1 to the charged-lepton report and Koide check to be independently followed. Each edge is typed with the manuscript's own claim vocabulary:

**Edge types:** DEF (definition) · ADM (admissibility rule) · MATH (mathematical implication) · UNIQ (uniqueness/exclusion argument) · CONST (constitutive identification) · INTERP (interpretation) · CAL (calibration) · EMP (empirical validation).

Adequacy flags: **[OK]** adequately explained for the intended reader in the manuscript itself; **[CARD]** adequately supported but the visible justification lives mainly in the cards; **[THIN]** asserted in both with limited reader-visible justification.

---

## A. Foundation layer (§§1–2)

| # | From → To | Type | Manuscript locus | Card support | Adequacy |
|---|---|---|---|---|---|
| A1 | Axiom (existence is relational distinguishability) → I = 1 | MATH | §1.1 | AX_001_001, THM_002_007 | [OK] one cut, admitted side counts one |
| A2 | Axiom → positive quantity domain 𝒟⁺ (no zero object, no signed primitives) | ADM | §1.2 | GUARD_001_008, IMPORT_001_007 | [OK] |
| A3 | 𝒟⁺ order properties → cancellation theorem | MATH | §1.2 | THM_002_003 | [OK] proof sketch in-text |
| A4 | Axiom → no external background; measurement = comparison against admitted standard | ADM | §1.3–1.4 | GATE_001_003 | [OK] |
| A5 | Ledger + transfer definition → conservation of admitted content | MATH | §2.1–2.3 | DEF_002_004, LEM_002_005 | [OK] |
| A6 | Declared involution ι → pairwise balance (Law of Symmetry Conservation) | DEF+MATH | §2.4 | DEF_002_010 | [OK] |
| A7 | Lawful generation → 2N record count; reachable ⇔ balanced | MATH | §2.5 | THM_002_012 | [OK] |
| A8 | Erasure rule (w·w̄ ≡ ε only) → persistence criterion | DEF | §2.6 | THM_002_011 | [OK] |
| A9 | Persistence criterion → three-register threshold (∃ persisting u ⇔ \|R\| ≥ 3) | MATH+UNIQ | §2.7 | THM_002_011, THM_003_012 | [OK] |
| A10 | Persisting unit re-identification (Relational Lift) → second degree of freedom | MATH | §2.8 | LEM_002_008 | [THIN] in-text: "two-endedness is itself a second degree of freedom" is asserted compactly |
| A11 | Complete orientation-preserving closure → t_base = 2π (angular extent) | MATH | §2.8 | THM_002_014 | [CARD] the card's extent-vs-winding non-circularity argument (2π read off a static closed object; extent = 2nd DoF, count = 1st DoF) is the load-bearing justification; in-text this is fences + assertion |
| A12 | t_base and unit servicing → m_base = 1/(2π), m_base·t_base = I | MATH | §2.8 | THM_002_014 §5 (non-erasure grounding) | [OK] identity itself clear; grounding in non-erasure is card-side |

## B. Base book layer (§3)

| # | From → To | Type | Manuscript locus | Card support | Adequacy |
|---|---|---|---|---|---|
| B1 | Closure traversal → τ = 2π (inherited from t_base) | DEF | §3 | DEF_003_002 | [OK] |
| B2 | m·τ = I with I = 1 → m = 1/(2π) | MATH | §3 | DEF_003_003 | [OK] — this m is the single coefficient of the eventual mass law |
| B3 | Three-register threshold → c = 3 connectivity channels | CONST | §3 | DEF_003_005, THM_003_012 | [OK] the manuscript is explicit that this is a *reading* of the threshold at the book layer ("the two readings must not be collapsed") |
| B4 | Rooted records + fairness + non-erasure → Cap = c·c = 9 (excluding 3 and 6) | UNIQ | §3 | THM_003_013 | [CARD] in-text excludes the unrooted quotient but not the "6" alternative; card does both |
| B5 | Cap, m → E = m·Cap = 9/(2π) | DEF | §3 | DEF_003_014 | [OK] with explicit non-SI fences |
| B6 | Paired completion of capacity account → G = Cap·τ = 18π | MATH | §3 | THM_003_022 | [THIN] densest passage in the paper; the "promoted pointwise co-reading" argument is compressed and reads as imported formalism |

## C. Geometry layer (§4)

| # | From → To | Type | Manuscript locus | Card support | Adequacy |
|---|---|---|---|---|---|
| C1 | Three channels + two-active/one-idle transfer edge → unique 12-vector orbit | UNIQ | §4.1 | LEM_004_006, THM_004_027 | [OK] BCC excluded on transfer-typing grounds, stated |
| C2 | 12-orbit → Λ_FCC (even-sum lattice), index 2, covolume 2 | MATH | §4.2 | DEF_004_003, LEM_004_025 | [OK] explicit generator identity |
| C3 | Minimal shell norm → η = √2 edge invariant | MATH | §4.2 | THM_004_019 | [OK] — later reappears as the 1/√2 in §12's operators (see G2) |
| C4 | Half-space system → RD cell census (12 facets, 14 vertices, Vol = 16u³) | MATH | §4.3 | THM_004_007, THM_004_010 | [OK] |
| C5 | Inball/cell → D = π/(3√2); Ω = 1 − D | MATH | §4.4–4.5 | THM_004_011, DEF_004_012 | [OK] normalization cancellation stated |

## D. Runtime/aperture/observer layer (§§5–9) — machinery consumed downstream

| # | From → To | Type | Manuscript locus | Card support | Adequacy |
|---|---|---|---|---|---|
| D1 | Ω → per-tick feed; threshold crossings → escapements; ΔI = 1 posting | DEF+MATH | §5.1–5.4 | THM_005_009/010, DEF_005_011 | [OK] |
| D2 | Exact Ω bounds → {3,4} staircase; first jump 2→4 | MATH | §5.5–5.6 | THM_005_017, THM_005_023 | [OK] |
| D3 | Histories + internal action + u_Φ → resolution floor and aperture | DEF+MATH | §6 | DEF_006_002–005, THM_006_007, THM_006_012 | [OK] |
| D4 | Tick↔closure bijection; rate equality | MATH | §7.4 | THM_007_007/008 | [OK] |
| D5 | Update/closure identity (one completion relation-token) | MATH+UNIQ | §7.6 | THM_007_012, LEM_007_011 | [OK] two-step rival-exclusion argument is visible in-text |
| D6 | Observer = readout locus + reference role; reads, never creates | DEF | §8.1–8.3 | DEF_008_002/003, ROLEDEF_008_014 | [OK] |
| D7 | Clockhood → time readout t(L) = I·t_base; support readout m_base | DEF | §8.4–8.6 | DEF_008_006/008, ROLEDEF_008_004 | [OK] |
| D8 | Reciprocal-pair reporting map; SI as special case | DEF+CAL | §8.7 | BRIDGE_008_009 | [OK] |
| D9 | Presentation discipline: recovery before operations; displays license no algebra | ADM | §9 | GATE_009_001/003, DEF_009_002 | [OK] |

## E. Disambiguation and carried-record layer (§§10–11)

| # | From → To | Type | Manuscript locus | Card support | Adequacy |
|---|---|---|---|---|---|
| E1 | Four-cell frame + reference role → S_flow = (c−1)/c = 2/3 | MATH | §10.2 | THM_010_013 | [OK] |
| E2 | S_flow ≠ ν(Π_o) as typed objects despite equal value | ADM/UNIQ | §10.3–10.4 | THM_010_013, THM_016_001 | [OK] — an anticipatory anti-numerology firewall |
| E3 | Ψ-closure event → one event, two faces, (n_post, n_route) = (2,1), exact recovery | DEF+MATH | §11 | DEF_011_001, LEM_011_003, LEM_016_006 | [OK] in-text; the *origin* of the (2,1) counts is card-side (DEF_011_001) |

## F. Spectral layer (§12)

| # | From → To | Type | Manuscript locus | Card support | Adequacy |
|---|---|---|---|---|---|
| F1 | Rooted one-cell record → Π_o = E_0 + E_1 on V = ℂ[ℤ/3ℤ] | DEF | §12.1 | THM_016_001 §2 | [OK] |
| F2 | Reynolds average + valuation → ν(Π_o) = A#_o = Φ_o = 2/3 | MATH | §12.1 | THM_016_001 §2 | [OK] both routes shown in-text |
| F3 | Action character ρ = exp(iσ·2/3) → three cube roots ζ with phase 2/9 | MATH | §12.1 | THM_016_001 §3 | [THIN] the completeness of the cube-root list is provable in a line, but *why* the spectral construction consumes the cube roots (three-branch structure) gets one sentence in-text |
| F4 | Coupling radius → operator coefficient 1/√2 in A_{σ,j} | MATH | §12.2 (bare) | THM_016_001 §1 (‖k_e(o)‖ = √2, u²+v² = 1/2) | **[CARD-ONLY]** the manuscript never states where 1/√2 comes from — the single clearest self-containment gap in the chain |
| F5 | Fourier diagonalization → λ_k = 1 + √2·cos(2/9 + 2πk/3); D3 orbit; unordered spectrum | MATH+UNIQ | §12.2 | THM_016_001 §§4–7 | [OK] |
| F6 | Strict ordering 0 < λ_min < λ_mid < λ_max | MATH | §12.2 | THM_016_001 §6 | [OK] inequalities displayed |
| F7 | Counting adjoint + nine-incidence book → M_read(A) = m·A†A, exponent s = 1 forced | UNIQ | §12.3 | THM_016_003 | [OK] the m·9^s = 9m argument is displayed |
| F8 | Quadratic supports q = mλ² → exact intrinsic ratios | MATH | §12.3 | THM_016_003 | [OK] coefficient cancellation explicit |

## G. Finite-screen layer (§13)

| # | From → To | Type | Manuscript locus | Card support | Adequacy |
|---|---|---|---|---|---|
| G1 | Taylor bounds + Pell certificates → 206 < R_int < 207; n_mid = 206 | MATH | §13.1 | BRIDGE_016_007 §1 | [OK] fully checkable |
| G2 | Two-face record + 206 → Γ_dir, Γ_route (206-element supports over common 3-root carrier) | CONST | §13.2 | BRIDGE_016_007 §2, LEM_016_006 | [THIN] the *construction* is exact; the *reason* the middle-rank count is the cardinality of face-attached supports is asserted, not argued, in both public sources |
| G3 | Free pushout → 409 = 206 + 206 − 3 (excluding 406 and 412) | UNIQ | §13.3 | BRIDGE_016_007 §3 | [OK] both alternatives excluded in-text |
| G4 | Completed count N → regular N-gon on unit-diameter circle → s_N = N·sin(π/N)/π | MATH | §13.4 | BRIDGE_016_007 §4 | [OK] winding argument summarized in card; in-text stated compactly |
| G5 | Screen acts once, post-quadratic, **middle rank only** | CONST/UNIQ | §13.4 | BRIDGE_016_007 §4 + falsifier 11 | **[THIN]** the public materials assert middle-only placement (with recovery guarantees) but give no reader-visible argument excluding screen action on the maximum rank — the predictable referee question is unanswered |

## H. Reporting and validation layer (§§14–15)

| # | From → To | Type | Manuscript locus | Card support | Adequacy |
|---|---|---|---|---|---|
| H1 | Rank triple → lepton names (min,mid,max) → (e,μ,τ) | CONST (naming) | §14.1 | ROLEDEF_016_004 | [OK] as a naming convention; the *physical* constitutive claim (these supports are what an observer reads as charged-lepton mass) rests on §8's support readout and is nowhere stated as a single sentence — see G2/§14 review |
| H2 | Ratio preservation + electron standard → unique linear bridge ℬ(q) = 𝒮_e·q | CAL | §14.2 | BRIDGE_016_008 | [OK] pointwise determination displayed |
| H3 | ℬ → three-entry report (M_e, M_μ, M_τ) | MATH | §14.3 | THM_016_009 | [OK] |
| H4 | Report ratios → Koide functional; scale cancellation | MATH | §15.1 | LEM_009_005 | [OK] |
| H5 | Q_K^out vs 2/3 benchmark → ≈1.35 ppm consistency | EMP | §15.2 | THM_016_009 + manuscript computation | [OK] with explicit failure conditions for the independence claim |

---

## Reader-visibility summary

- The chain from I = 1 to the report is **complete at the public level**: every load-bearing node appears in the manuscript, and every manuscript claim checked so far has a supporting card.
- **Three edges carry the paper's real inferential risk** and are the thinnest in reader-visible justification:
  - **F4** (1/√2 coefficient — provenance card-only; a one-sentence repair restores self-containment);
  - **G2 + G5** (why the two-face 206-support construction exists at all, and why its screen touches only the middle rank — asserted with exact machinery but not argued against the obvious alternative in either public source);
  - **B6** (G = 18π identification — densest and least-motivated passage, though G is not consumed by the mass chain, so the exposure is stylistic rather than derivational).
- Everything in layer D except the aperture value A# and the two-face record is **not consumed** by the mass derivation; the map makes visible that §§5–9 function as program infrastructure plus typing discipline rather than as premises of §§12–14 (relevant to length/scope assessment, not to validity).
