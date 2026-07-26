# Master Symbol Ledger

Every mathematical symbol used in the manuscript. Locations use section numbers (the manuscript has no equation numbers — itself a finding, see SYMBOL_OCCURRENCE_AUDIT). Occurrence counts and first/last locations were generated mechanically from the full text (`occurrence_data.tsv`) and verified against the PDF for every load-bearing symbol.

Legend — Dim: dimensionless (dl) or physical (phys). Status: intrinsic (INT), observer-relative (OBS), calibration (CAL), empirical (EMP), presentation/bookkeeping (PRES), n/a. Collision: CLEAR / AMBIG (overloaded but locally disambiguated) / CONFLICT (incompatible meanings).

| Symbol | Plain text | First occ. | First def. | Meaning | Type | Dim | Scope | Status | EQ-card source | Variants | Collision | Notes |
|---|---|---|---|---|---|---|---|---|---|---|---|---|
| I | I | §1.1 | §1.1 | first existence count; later generic completed-unit count | count | dl | global | INT | AX_001_001, THM_002_007 | I(γ₁,γ₂), I_bulk, I_screen, ΔI | CLEAR | value 1; also functions as unit account threshold |
| 𝒟⁺ | D+ | §1.2 | §2.1 | strictly positive quantity domain | ordered semigroup | dl | global | INT | DEF_002_001 | 𝒟⁺_act (§6.2) | CLEAR | no zero, no inverses |
| q | q | §1.2 | §1.2 | generic positive quantity; later quadratic supports; Koide inputs | element of 𝒟⁺ | dl (until §14) | local per section | INT→CAL | THM_016_003 | q_s(x), q_min/mid/max, q_e/μ/τ, q₁,q₂,q₃ | AMBIG | heavy but always subscript-disambiguated |
| Adm, Std_L, Cmp_L, Meas_L, Unit_L, Report_L | — | §1.4 | §1.4 | admissibility/standard/comparison/measurement predicates | predicates | n/a | global | ADM | GATE_001_003 | — | CLEAR | |
| L | L | §1.4 | §1.4 (context), §8.1 (object) | readout context, later readout locus | label/relational standpoint | n/a | global | OBS | DEF_008_002 | — | CLEAR | §1.4 "future readout context" forward-declares §8 |
| R | R | §2.1 | §2.1 | finite set of relationship registers | set | n/a | §§2–5 | INT | DEF_002_001 | \|R\| | AMBIG | R also appears in §13.4 card as rotation; in-manuscript rotation unnamed; R_mid/min, R_max/min are distinct ratio symbols |
| h | h | §2.1 | §2.1 | holdings state (partial map) | partial map R→𝒟⁺ | dl | §2 | INT | DEF_002_001 | h′, supp(h) | CLEAR | |
| T(A→B;q) | T | §2.2 | §2.2 | transfer operation | operation | n/a | §2 | INT | DEF_002_004 | — | CLEAR | |
| σ | sigma | §2.2 | §2.2 | orientation/side tag | label (no algebra) | n/a | global | INT | DEF_002_002 | σ ∈ Σ_rel (§2.2); σ ∈ {+1,−1} (§12) | AMBIG | §2 label-only with no algebra; §12 uses ±1 *in an exponential* — the ±1 realization is licensed by the carried-orientation discussion but the type shift (label → sign factor in exp) is never explicitly bridged in-text |
| Σ_rel | Sigma_rel | §2.2 | — (never formally defined) | set of orientation labels | set | n/a | §2 | INT | DEF_002_002 | — | CLEAR | **used once, never defined in-text**; card defines it |
| ι | iota | §2.4 | §2.4 | declared involution pairing record co-readings | involution | n/a | §2 | INT | DEF_002_010 | ι_or; ι_post, ι_route (§11); ι_dir, ι_route (card §13) | AMBIG | §11 reuses ι for tagged injections — different object, same glyph, subscripts disambiguate |
| mult_X | mult | §2.4 | §2.4 (contextual) | record multiplicity | count | dl | §2 | PRES | DEF_002_010 | — | CLEAR | |
| ε | epsilon | §2.6 | §2.6 | empty walk | identity element | n/a | §§2,6 | INT | THM_002_011 | ε₄ (§5.5, different: overshoot) | AMBIG | ε₄ = 4Ω−1 is a distinct object; subscript distinguishes |
| w, u (walks) | w,u | §2.6 | §2.6 | walks; closed walks | walks | n/a | §2 | INT | THM_002_011 | w·w̄ | AMBIG | u reused: §4.3 normalization parameter u>0, §5.2 u_tick, §6.3 u_Φ, §8.1 registered updates u — four+ meanings, all section-local |
| t_base | t_base | §2.8 | §2.8 | angular extent of one closure = 2π | dl extent | dl | global | INT | THM_002_014 | τ (§3 alias by inheritance) | CLEAR | explicitly not a clock reading |
| m_base | m_base | §2.8 | §2.8 | conjugate support 1/(2π) | dl support | dl | global | INT | THM_002_014 §5 | — | CLEAR | kept distinct from active m (§8.6) — distinction stated in-text |
| τ | tau | §3 | §3 | closure-traversal label, value 2π | dl extent | dl | §§3–8 | INT | DEF_003_002 | — | **AMBIG** | glyph collision with lepton subscript τ in M_τ, r_τ, q_τ (§§14–15); context disambiguates but same italic glyph |
| m | m | §3 | §3 | active mass / closure-service support = 1/(2π) | dl coefficient | dl | global | INT | DEF_003_003 | m_base distinct | CLEAR | the single coefficient of the mass law |
| c | c | §3 | §3 | connectivity-channel count = 3 | count | dl | global | INT | DEF_003_005 | c⊗2 (§8.8); c_SI (§14.2, speed of light in reporting) | AMBIG | §8.8 explicitly fences c from speed of light; c_SI subscript separates |
| Cap | Cap | §3 | §3 | rooted-position incidence count = 9 | count | dl | global | INT | THM_003_013 | — | CLEAR | |
| E | E | §3 | §3 | book channel-distribution total = 9/(2π) | dl quantity | dl | §§3,8 | INT | DEF_003_014 | E_r, E_rp (§§10.4,12) matrix units — different object | **AMBIG** | E alone = book energy; subscripted E = projector/matrix unit; same italic font |
| G | G | §3 | §3 (value), §7.7 (role) | closure-bookkeeping value 18π; §7 the G-operation by role | value / operation | dl / n/a | §§3,7,10 | INT | ROLEDEF_003_011, THM_003_022 | G₃ (group, §3) | AMBIG | the value/role split is *explicitly declared* in §7.7; G₃ is a distinct group symbol |
| G₃ | G3 | §3 | §3 | channel relabeling group S₃⋉(ℤ₂)³, order 48 | group | n/a | §3 | PRES | LEM_003_010 | — | CLEAR | |
| M_exist, M_base, M_cell | — | §3,§3,§4.6 | in place | bookkeeping display arrays | organizational display | n/a | §§3–4,10 | PRES | DEF_003_004/015, DEF_004_020 | — | CLEAR | explicitly non-algebraic |
| Λ_FCC | Lambda_FCC | §4.2 | §4.2 | even-sum integer lattice | lattice | n/a | §4 | PRES | DEF_004_003 | — | CLEAR | presentation object |
| S₁₂ | S12 | §4.2 | §4.2 | minimal shell (12 vectors) | set | n/a | §4 | PRES | LEM_004_006 | — | CLEAR | |
| η | eta | §4.2 | §4.2 | edge invariant √2 | dl norm | dl | global | INT | THM_004_019 | — | CLEAR | reappears (unstated) as 1/√2 in §12 operators — see UNDEFINED_SYMBOLS |
| C_u | C_u | §4.3 | §4.3 | RD cell polytope, normalization u | polytope | n/a | §4 | PRES | THM_004_007 | C_{1/2} | AMBIG | C heavily overloaded across paper — see collision report |
| u | u | §4.3 | §4.3 | cell normalization parameter > 0 | scalar | dl | §4 | PRES | THM_004_007 | — | AMBIG | see walks row |
| r | r | §4.3 | §4.3 | inradius (model-internal) | scalar | dl | §4 | PRES | THM_004_010 | r ∈ R registers (§2); r basis index (§12); r₀,r₁,r₂ roots (§11.4); r_int, r_closure rates (§7); r_μ, r_τ ratios (§15) | **AMBIG** | six distinct section-local uses of the letter r |
| D | D | §4.4 | §4.4 | filled share π/(3√2) | dl share | dl | global | INT | THM_004_011 | 𝒟⁺, 𝒟(L) script variants | AMBIG | font distinguishes; D₃ group subscripted |
| Ω | Omega | §4.5 | §4.5 | residual share 1 − π/(3√2) | dl share | dl | global | INT | DEF_004_012 | Ω_geom, Ω_pack, Ω_cell^slot, ω_cell (§5.2) | AMBIG | four aliases equated in one display §5.2 — deliberate typed handoff, stated |
| REF(ξ) | REF | §4.7 | §4.7 | static site-cell referent | map | n/a | §4 | PRES | THM_004_018 | — | CLEAR | |
| ξ | xi | §4.2 | §4.2 | lattice-site label | label | n/a | §4 | PRES | — | — | CLEAR | §12 preamble explicitly notes ξ is §4's site label to avoid clash with λ |
| S_res | S_res | §5.1 | §5.1 | residual register (partial holding) | partial holding | dl | §§5,7,10 | INT | DEF_005_003 | S_res,x (per cell, §10.1) | CLEAR | never stores zero |
| k, K | k,K | §5.1/§5.4 | §5.1 | update index / cycle count | indices | dl | §5 | INT | DEF_005_012 | K_x per cell | AMBIG | k vs K vs x division of labor never stated in one place (see occurrence audit) |
| ω_cell | omega_cell | §5.2 | §5.2 | per-tick feed = Ω | dl increment | dl | §§5,7 | INT | DEF_005_007 | — | CLEAR | |
| u_tick(x) | u_tick | §5.2 | §5.2 | accumulated input xΩ | scalar | dl | §5 | INT | DEF_005_007 | — | CLEAR | |
| N_tick(x) | N_tick | §5.2 | §5.2 | **escapement count** ⌊xΩ⌋ (not tick count) | count | dl | §§5,7 | INT | DEF_005_006 | — | CLEAR | manuscript twice warns about the misleading glyph — honest but the name itself invites the misreading it warns against |
| ΔI | Delta I | §5.3 | §5.3 | forced unit posting = 1 | count | dl | global | INT | THM_005_009 | — | CLEAR | |
| ⊕, ⊖, ⪰ | oplus etc. | §5.3–5.4 | §5.3–5.4 | positive accumulation / posting removal / positive-gap order | operations/order | n/a | global | INT | DEF_005_011 | — | CLEAR | ⊖ explicitly not signed subtraction |
| T_rt(K) | T_rt | §5.4 | §5.4 | completed unit-accounts by cycle K | count | dl | §5 | INT | THM_005_015 | — | CLEAR | equals N_tick at empty start |
| frac(·) | frac | §5.4 | §5.4 | fractional part (external closed form) | function | dl | §5 | PRES | THM_005_015 | — | CLEAR | typed as account reading, not ontology |
| ε₄ | eps4 | §5.5 | §5.5 | overshoot 4Ω − 1 | scalar | dl | §5 | INT | THM_005_017 | — | CLEAR | |
| ℋ(A,B) | H(A,B) | §6.1 | §6.1 | admissible relational walks A→B | set | n/a | §6 | INT | DEF_006_002 | — | CLEAR | A,B here are events, not §2 registers — local reuse |
| 𝒮_Φ | S_Phi | §6.2 | §6.2 | internal action functional | map ℋ→𝒟⁺_act | dl | §6 | INT | DEF_006_003 | — | AMBIG | script S also used for 𝒮_e (§14) — different font-family object |
| u_Φ | u_Phi | §6.3 | §6.3 | internal resolution unit | element 𝒟⁺_act | dl | §§6–7 | INT | DEF_006_004 | — | CLEAR | explicitly not ℏ |
| g_Φ | g_Phi | §6.4 | §6.4 | action gap (σ, \|g_Φ\|) | tagged positive excess | dl | §6 | INT | DEF_006_005 | \|g_Φ\| | CLEAR | |
| φ_rel | phi_rel | §6.6 | §6.6 | relative phase 2π·g_Φ mod 2π | phase | dl | §6 | INT | ROLEDEF_006_008 | — | CLEAR | |
| A_Φ | A_Phi | §6.7 | §6.7 | coherence aperture (typed window) | typed object | n/a | §6 | INT | DEF_006_010 | — | CLEAR | |
| R₁,R₂,R₃ | R1-3 | §6.8 | §6.8 | aperture regimes | sets | n/a | §6 | INT | THM_006_012 | — | AMBIG | R again; local |
| ℏ | hbar | §6 | §6 (bridge clause) | bridge-side action quantum | phys constant | phys | bridge only | EMP | BRIDGE_006_009/013 | ℏ_eff | CLEAR | explicitly non-internal |
| A# | A# | §6.10 | §6.10 | focusing parameter 0<A#≤1 | scalar | dl | bridge | OBS | BRIDGE_006_013 | A#_o (§12: aperture value 2/3) | **AMBIG** | A# (bridge focusing) vs A#_o (intrinsic one-pass aperture 2/3) share the # decoration; §12 value is intrinsic, §6 parameter is bridge-side — subscript o is the only separator, nowhere remarked |
| I_bulk, I_screen | — | §6.10 | §6.10 | bridge readout counts | scalars | dl | bridge | OBS | BRIDGE_006_013 | I_bulk,o (§12.1) | AMBIG | I_bulk,o = 1 in §12 is an intrinsic completed unit — same base symbol crossing the intrinsic/bridge boundary; subscript o separates |
| r_int, r_closure | — | §7.1/§7.4 | §7.1 | internal completion rates | discrete densities | dl | §7 | INT | DEF_007_001, THM_007_008 | — | CLEAR | |
| cost[γ] | cost | §7.5 | §7.5 | service/completion burden | element 𝒟⁺ | dl | §7 | INT | DEF_007_009 | — | CLEAR | not energy (stated) |
| 𝒟(L) | D(L) | §8.1 | §8.1 | registered content at locus | set | n/a | §8 | OBS | DEF_008_002 | — | CLEAR | |
| reg(L,u) | reg | §8.2 | §8.2 | registration relation | predicate | n/a | §8 | OBS | DEF_008_003 | — | CLEAR | |
| Obs(X,ℓ) | Obs | §8.3 | §8.3 | observer/reference role | role predicate | n/a | §8 | OBS | ROLEDEF_008_014 | — | CLEAR | |
| t(L), s(L) | t(L),s(L) | §8.5/§8.6 | in place | time/support readouts | dl readouts | dl | §8 | OBS | DEF_008_006/008 | t_obs, s_obs | CLEAR | |
| 𝒮_e | S_e | §14.2 | §14.2 | electron reporting scale M_e^std/(mλ²_min) | positive scale | phys | §14 | CAL | BRIDGE_016_008 | — | AMBIG | script S; see 𝒮_Φ row |
| S_flow | S_flow | §10.2 | §10.2 | content-distinguishable fraction (c−1)/c = 2/3 | count ratio | dl | §10 | OBS | THM_010_013 | C4inv | CLEAR | explicitly separated from ν(Π_o) |
| C4inv | C4inv | §10.3 | §10.3 | the C4 invariant := S_flow | count ratio | dl | §10 | OBS | THM_010_013 | — | CLEAR | "C4" itself never expanded as "four-cell" in a definition — see terminology ledger |
| Π_o | Pi_o | §10.4 | §10.4 (partial), §12.1 (full) | rooted two-active/one-idle projector | operator | n/a | §§10,12 | INT | THM_016_001 | Π₀ (§12.3 display 3Π₀ — subscript 0 vs o!) | **CONFLICT (typographic)** | §12.3 writes U_J = 3Π₀ with subscript zero where Π_o (subscript letter o) is meant; one-glyph inconsistency in a load-bearing display |
| ν(·) | nu | §10.4 | §12.1 | normalized support valuation | valuation | dl | §§10,12 | INT | THM_016_001 | — | CLEAR | used §10.4 before §12 definition (forward use) |
| P | P | §10.4 | §12.1 | cyclic shift on V | unitary operator | n/a | §§10,12 | INT | THM_016_001 | P^r, P^{-1} | CLEAR | used §10.4 before §12 definition |
| V, 𝟏_V | V | §12.1 | §12.1 | carrier ℂ[ℤ/3ℤ]; identity | space/operator | n/a | §12 | INT | THM_016_001 | — | AMBIG | V also §4.3 vertex sets V₃,V₄ — subscripted, local |
| E_r, E_rp | E_r | §10.4 (E₀+E₁) | §12.1 (kets), §12.3 (E_rp) | spectral projectors / matrix units | operators | n/a | §§10,12 | INT | THM_016_001/003 | — | AMBIG | forward-used in §10.4; collision with book E noted above |
| A#_o, Φ_o | A#_o, Phi_o | §12.1 | §12.1 | one-pass action aperture and phase = 2/3 | scalars | dl | §12 | INT | THM_016_001 | — | AMBIG | see A# row |
| ρ_{o,σ} | rho | §12.1 | §12.1 | action character exp(iσ2/3) | phase factor | dl | §12 | INT | THM_016_001 | ρ_mid (§13.1, fractional part) | AMBIG | subscripts separate |
| ζ_{o,σ,j} | zeta | §12.1 | §12.1 | cube roots of ρ | phase factors | dl | §§12–13 | INT | THM_016_001 | ζ̄ | CLEAR | |
| A_{σ,j} | A_sigma_j | §12.2 | §12.2 | Hermitian screen operators | operators | n/a | §12 | INT | THM_016_001 | — | CLEAR | the 1/√2 coefficient is undefined in-text (see UNDEFINED_SYMBOLS) |
| λ, λ_k, λ_min/mid/max | lambda | §12 (preamble) | §12.2 | intrinsic spectral amplitudes | scalars | dl | §§12–15 | INT | THM_016_001/003 | λ^scr_{σ,j;k}; cards use Λ | CLEAR | manuscript flags the §4 ξ/λ separation explicitly |
| α | alpha | §12.2 | §12.2 | reference phase 2/9 | scalar | dl | §12 | INT | THM_016_001 | **x = 2/9 in §13.1** | **CONFLICT (naming)** | same object carries α in §12 and x in §13.1 with no cross-reference |
| C, J | C,J | §3/§12.3/§11.4/§13.2 | per section | 3-element register/index/root sets; J = C×C | sets | n/a | section-local | INT | THM_003_013, THM_016_003, LEM_016_006 | C_root, C = {0,1,2}, C = {A,B,C} | **AMBIG (systemic)** | the letter C names at least four related 3-element objects plus the polytope C_u; each is locally defined; the *deliberate* identity claims (root carrier = C₃ structure) vs accidental letter reuse are not always distinguishable for the reader |
| M_read | M_read | §12.3 | §12.3 | quadratic-support map m·A†A | map | dl | §§12,Concl. | INT | THM_016_003 | — | CLEAR | |
| ℱ_s(B) = mB^s | F_s | §12.3 | §12.3 | positive-real response family | family | dl | §12.3 | INT | THM_016_003 | s exponent | AMBIG | s reused: s(L), s_N, s_409, standard s (§1.4) — all distinct |
| q_min/mid/max | — | §12.3 | §12.3 | intrinsic quadratic supports mλ² | scalars | dl | §§12–14 | INT | THM_016_003 | — | CLEAR | |
| R^int_, R^scr_ ratios | R_mid/min etc. | §12.3 | §12.3 | intrinsic/screened support ratios | scalars | dl | §§12–15 | INT | THM_016_003, BRIDGE_016_007 | — | CLEAR | |
| n_mid, ρ_mid | — | §13.1 | §13.1 | floor 206 and fractional part | count/scalar | dl | §13 | INT | BRIDGE_016_007 | — | CLEAR | |
| Γ_dir, Γ_route, Γ_scr | Gamma | §13.2–13.3 | §13.2 | 206-element supports; 409-class pushout | sets | n/a | §13 | INT | BRIDGE_016_007 | — | CLEAR | |
| U_dir, U_route | U | §13.2 | §13.2 | 203-element disjoint sets | sets | n/a | §13 | INT | BRIDGE_016_007 | U_J (§12.3, all-ones operator) | AMBIG | U_J is an operator, subscript J separates |
| s_N, s_409 | s409 | §13.4 | §13.4 | regular-screen factor N·sin(π/N)/π | scalar | dl | §§13–15 | INT | BRIDGE_016_007 | π_L(N) perimeter | CLEAR | |
| n_post, n_route | — | §11.1 | §11.1 | face counts (2,1) | counts | dl | §§11,13 | INT | LEM_016_006 | — | CLEAR | explicitly not combined |
| Rec_2f, Recover_*, Render_* | — | §11.2–11.3, §9 | §9 | construction records and recovery maps | records/maps | n/a | §§9,11 | PRES | DEF_009_002, GATE_009_001 | Rec_O, RCI_O, Idx_O, OpRec_O | CLEAR | |
| M_e^std | Me_std | §14.2 | §14.2 | CODATA electron mass-energy standard | phys datum | phys | §§14–15 | EMP/CAL | BRIDGE_016_008 | — | CLEAR | sole empirical derivation input |
| c_SI | c_SI | §14.2 | §14.2 | SI speed of light (reporting) | phys constant | phys | §14 | EMP | THM_014_004 | — | CLEAR | |
| ℬ | B | §14.2 | §14.2 | ratio-preserving reporting map | linear map | phys | §14 | CAL | BRIDGE_016_008 | — | CLEAR | |
| M_e,M_μ,M_τ (report/out) | — | §14.3 | §14.3 | three-entry mass report | phys reports | phys | §§14–15 | CAL | THM_016_009 | — | CLEAR | |
| 𝒬_K | Q_K | §15.1 | §15.1 | Koide shape functional | functional | dl | §15 | INT | LEM_009_005 | 𝒬_K^out | CLEAR | |
| r_μ, r_τ | r_mu,r_tau | §15.1 | §15.1 | derived dimensionless ratios | scalars | dl | §15 | INT | THM_016_009 | — | CLEAR | |
| Δ_K | Delta_K | §15.2 | §15.2 | Q_K^out − 2/3 | scalar | dl | §15 | EMP (comparison) | — | — | CLEAR | |

**Ledger coverage note.** Symbols appearing only inside §9's formal displays (π_idx, π₁, π₂, Φ as generic later operation, κ unit-rescale factor, Y/Z rendered reports, 𝒜 rendering context) and §4's V₃/V₄ vertex classes are included in the occurrence audit but are equation-local with clear one-shot definitions; none collides beyond the notes above. Greek letters π (circle constant) and standard set/logic notation are used conventionally throughout.
