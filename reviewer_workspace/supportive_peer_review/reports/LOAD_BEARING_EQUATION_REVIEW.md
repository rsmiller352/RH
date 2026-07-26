# Load-Bearing Equation Review

Every equation carrying theory-specific inferential burden, checked for: why introduced / objects defined / permitting result / what it establishes / what it excludes / intrinsic-vs-observer status / dimensional status / what follows — plus cross-reference to its public card. Routine algebra omitted per charter. (The manuscript numbers no equations; entries are identified by section and content.)

| # | Equation (locus) | Why introduced / permitted by | Establishes / excludes | Status typing | Card | Verdict |
|---|---|---|---|---|---|---|
| 1 | I = 1 (§1.1) | one cut, admitted side | first count; excludes zero/negative primitives | intrinsic, dl | AX_001_001, THM_002_007 | **Full pass** |
| 2 | a+q=b+q ⇔ a=b (§1.2) | positivity + total order | restricted subtraction as theorem; excludes inverse elements | intrinsic | THM_002_003 | Full pass |
| 3 | Meas_L(x;s)↓ ⇔ Adm∧Std∧Cmp (§1.4) | admission rules | measurement admissibility; excludes primitive scalars | admissibility | GATE_001_003 | Full pass |
| 4 | transfer semantics + Σh′=Σh (§2.2–2.3) | ledger defs | conservation; excludes leakage | intrinsic | DEF_002_004, LEM_002_005 | Full pass |
| 5 | balance predicate; \|X_n\|=2n (§2.4–2.5) | declared involution | reachable ⇔ balanced | intrinsic | DEF_002_010, THM_002_012 | Full pass |
| 6 | u persists ⇔ u≠ε ∧ ¬∃w(u=w·w̄) (§2.6) | single erasure rule | persistence criterion; excludes free-group reduction | intrinsic | THM_002_011 | Full pass |
| 7 | ∃u persists ⇔ \|R\|≥3 (§2.7) | walk formalism | three-register threshold | intrinsic | THM_002_011/THM_003_012 | Full pass |
| 8 | **t_base = 2π; m_base·t_base = I (§2.8)** | Relational Lift + non-erasure | base extents; excludes metric/clock readings | intrinsic, dl | THM_002_014 | **Partial pass** — what it *is* (total turning of a static closure; extent-DoF vs count-DoF) is card-side; in-text justification is fence-heavy, assertion-light. Repair: 2–4 sentences (§2 review). |
| 9 | m·τ = I ⇒ m = 1/(2π) (§3) | τ inherited; unit service | the single mass-law coefficient | intrinsic | DEF_003_003 | Full pass |
| 10 | **Cap = c·c = 9 (§3)** | rooted records + fairness + non-erasure | capacity; excludes 3 (canonical root/unrooted) — "6" exclusion card-only | intrinsic | THM_003_013 | Pass with note |
| 11 | **G = Cap/m = Cap·τ = 18π (§3)** | paired completion | closure-side aggregate; excludes matrix-position inference | intrinsic (accounting role) | THM_003_022 | **Partial pass** — densest passage; "value-free closure office" undefined in-text; not consumed downstream, so exposure is presentational |
| 12 | Λ_FCC = span{(0,1,1),(1,0,1),(1,1,0)} = even-sum lattice (§4.2) | forced 12-orbit | lattice identification; excludes BCC (transfer-typing) | presentation | DEF_004_003, LEM_004_025, THM_004_027 | Full pass |
| 13 | η = √2 (§4.2) | minimal shell norm | edge invariant | intrinsic, dl | THM_004_019 | Full pass — **but its reappearance as 1/√2 in eq. 20 is unstated (see 20)** |
| 14 | Vol(C_u)=16u³; Vor = C_{1/2}; Vol = 4√2r³ (§4.3) | half-space census | cell geometry; excludes farther-shell cuts | presentation | THM_004_007/010, LEM_004_008 | Full pass |
| 15 | D = π/(3√2); Ω = 1−D (§4.4–4.5) | inball/cell ratio | shares; excludes packing-optimality and density claims | intrinsic, dl | THM_004_011, DEF_004_012 | Full pass |
| 16 | update rule; T_rt = ⌊S₀+Kω⌋ (§5.4) | account discipline | runtime bookkeeping; excludes stored zero | intrinsic | DEF_005_011, THM_005_015 | Full pass |
| 17 | gaps∈{3,4} ⇔ 2√2<π<9√2/4 (§5.5) | exact Ω bounds | staircase; excludes other gap patterns | intrinsic | THM_005_017 | Full pass |
| 18 | floor/aperture: I = ⌊\|g_Φ\|⌋ (§6.5) | u_Φ + completion | resolution floor; excludes sub-unit records | intrinsic | THM_006_007 | Full pass |
| 19 | ν(Π_o)=2/3; A#_o=Φ_o=2/3 (§10.4, §12.1) | Reynolds + valuation + trace | one-pass aperture/phase; excludes S_flow identification | intrinsic | THM_016_001 | Full pass (double derivation in-text) |
| 20 | **A_{σ,j} = 𝟏 + (1/√2)ζP + (1/√2)ζ̄P⁻¹ (§12.2)** | rooted record + coupling | the spectral operators | intrinsic | THM_016_001 §1 | **FAIL on "objects defined": the coefficient 1/√2 has no in-text provenance** (card derives it from the coupling radius). The paper's most load-bearing display with its only unexplained constant. Repair: one sentence. (CI-1) |
| 21 | λ_k = 1+√2cos(2/9+2πk/3); ordering (§12.2) | Fourier diagonalization | intrinsic unordered spectrum; excludes labeled sectors | intrinsic | THM_016_001 §§3–6 | Full pass |
| 22 | **U_J = 𝟏+P+P⁻¹ = 3Π₀; Tr(U_J†U_J)=9 (§12.3)** | incidence book | response-power input | intrinsic | THM_016_003 | **Partial pass — Π₀ undefined and typographically collides with Π_o** (math verified correct). Repair: rename + half-sentence. (collision X2) |
| 23 | m·9^s = 9m ⇒ s = 1 (§12.3) | full-book closure | forced exponent; excludes fitted powers | intrinsic | THM_016_003 | Full pass — small and airtight |
| 24 | q = mλ²; ratio displays (§12.3) | eq. 23 | intrinsic ratios; coefficient cancels | intrinsic, dl | THM_016_003 | Full pass |
| 25 | 206 < R_int < 207 (§13.1) | Pell + Taylor propagation | floor 206; excludes decimals and measured input | intrinsic | BRIDGE_016_007 §1 | Full pass — showpiece |
| 26 | \|Γ_scr\| = 206+206−3 = 409 (§13.3) | free pushout | screen count; excludes 406, 412 | intrinsic | BRIDGE_016_007 §3 | Full pass |
| 27 | **s_N = N·sin(π/N)/π; (q_min, s_409·q_mid, q_max) (§13.4)** | regular N-gon from completed count | screen factor and its action | intrinsic → readout | BRIDGE_016_007 §4 | **Partial pass: formula fully derived; the "what it excludes" cell is empty for placement** — no public argument excludes screening the max rank. The paper's most consequential asserted-not-argued step. (CI-5) |
| 28 | ℬ(q) = 𝒮_e·q (§14.2) | ratio preservation + one anchor | unique calibration; excludes multi-point fitting | calibration | BRIDGE_016_008 | Full pass |
| 29 | three-entry report (§14.3) | eqs. 24, 27, 28 | the result | calibrated report | THM_016_009 | Full pass |
| 30 | 𝒬_K invariance; Q_K^out = 2/3 + 9.0×10⁻⁷ (§15) | scale-free shape | Koide consistency; excludes exact-identity claim | empirical check | LEM_009_005 | Full pass — see Koide audit for the undisclosed saturation identity |

## Summary
30 load-bearing equations reviewed. 25 full passes — an unusually high rate for a foundational manuscript, reflecting the paper's habit of typing each display's status and non-claims in adjacent prose. The five partial/failed entries concentrate exactly where the section reviews found them: #8 (2π justification), #11 (G passage), #20 (1/√2 — the only outright fail), #22 (Π₀ notation), #27 (middle-only placement). All five have small identified repairs; #20 and #27 are the two that matter most for a referee's verdict on the derivation chain.
