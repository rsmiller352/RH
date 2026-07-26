# Manuscript ↔ EQ-Card Notation Diff

Comparison of notation between the manuscript and the public cards for every symbol family checked during Phases 4–6. Verdicts: MATCH (identical), STYLE (systematic, harmless, documented here), DIFF (could confuse a reader moving between paper and cards).

| Object | Manuscript | Cards | Verdict | Notes |
|---|---|---|---|---|
| Spectral amplitudes | λ_k, λ_min/mid/max, λ^scr_{σ,j;k} (§12) | Λ_k, Λ_min/mid/max, λ^scr_{σ,j;k} (THM_016_001/003, BRIDGE_016_007) | **DIFF (systematic)** | cards use capital Λ for reference amplitudes where the manuscript uses lowercase λ; identical formulas. A reader cross-checking §13.1 against BRIDGE_016_007 §1 sees Λ_min there and λ_min in the paper. One-line convention note in the paper (or supplement README) would close it. |
| Spectral phase | α = 2/9 (§12); x = 2/9 (§13.1) | x = 2/9 (BRIDGE_016_007); α (THM_016_001 §4) | DIFF | the manuscript's own α/x split mirrors a card-side split; see collision X1 — fix in manuscript. |
| Screen operators | A_{σ,j} | A^scr_{σ,j} | STYLE | manuscript drops the "scr" superscript after introducing the objects; harmless. |
| Cube roots | ζ_{o,σ,j} | ζ^scr_{o,σ,j} | STYLE | same drop. |
| Projector | Π_o | Π_o | MATCH | but manuscript's §12.3 "3Π₀" (zero subscript, undefined) has **no card counterpart** — THM_016_003's corresponding display uses the explicit uniform projector; see collision X2. |
| Support law | M_read(A) = mA†A | M_read(A) = mA†A | MATCH | |
| Ratios | R^int_mid/min, R^scr_mid/min | R^int_mid/min, R^scr_mid/min | MATCH | |
| Floor certificates | Pell integers, sign-aware propagation summarized | full exact rationals for all four bounds plus two margin certificates | STYLE | appropriate division of labor (machinery in cards); the manuscript states the bounds' existence and degrees correctly. |
| 409 construction | Γ_dir, Γ_route, Γ_scr, C = C_root, U_dir, U_route | identical + q_409, f_N, R (rotation), Rec_409 | STYLE | the card's quotient map q_409, screen realization f_N, rotation R, and carried record Rec_409 have no manuscript symbols; the manuscript summarizes those steps in prose. Note the card's R (rotation) would collide with manuscript R-symbols if imported — it isn't. |
| Screen factor | s_N, s_409, π_L(N) | s_N, s_409, π_L(N) | MATCH | |
| Two-face record | ι_post, ι_route, Rec_2f, n_post, n_route | ι_post/ι_route (LEM_016_006); ι_dir/ι_route (BRIDGE_016_007 §2 for support injections) | STYLE | the dir/route vs post/route subscript shift between the two cards is mirrored by the manuscript's Γ_dir/Γ_route naming; internally consistent but the post↔dir correspondence (posting face ↦ "dir" support) is stated in neither the manuscript nor the cards in one sentence. Minor. |
| Electron bridge | ℬ, 𝒮_e, M_e^std | Bridge map with same structure; Q_scr triple | MATCH | |
| Koide | 𝒬_K, Q_K^out, Δ_K | Koide shape functional (LEM_009_005) | MATCH | card proves gauge cancellation in general form; manuscript instantiates. |
| Base quantities | I, τ, m, c, Cap, E, G, η, D, Ω | identical | MATCH | cards add internal decision tags (D-numbers) around them. |
| t_base / m_base | t_base = 2π, m_base = 1/(2π) | identical | MATCH | |
| Runtime | S_res, ω_cell, N_tick, T_rt, ΔI | identical | MATCH | |
| Aperture | u_Φ, g_Φ, A_Φ, φ_rel, A# | identical | MATCH | |
| Observer | L, 𝒟(L), reg, Obs, t(L), s(L) | identical (RO-series role names added) | STYLE | cards' RO-A…RO-G layer labels are internal and absent from the manuscript — correctly so. |
| C4 invariant | S_flow, C4inv | S_flow (THM_010_013, "C4-top readout invariant") | STYLE | the "C4" tag is internal spine vocabulary in both; the manuscript inherits it without expansion (see leakage audit). |

## Verdict
No notation difference changes any value, statement, or dependency. Two DIFF items (λ/Λ and α/x) deserve repair or a convention note because they sit exactly where a skeptical reader will cross-check the central computation. The cards' internal decorations (scr superscripts, RO labels, D-numbers, SRC hashes) are consistently absent from the manuscript — the right direction of separation.
