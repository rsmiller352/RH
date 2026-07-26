# Symbol Occurrence Audit

Method: mechanical occurrence extraction over the full manuscript text (`occurrence_data.tsv`, generated from `manuscript_fulltext.txt` with per-line regex matching; line numbers map to sections via the header table), followed by manual verification against the PDF for every load-bearing symbol and every flagged anomaly. For each symbol the audit checked: (1) ledger presence; (2) meaning stability across occurrences; (3) type stability; (4) scope compliance; (5) definition-before-use; (6) manuscript/EQ-card agreement.

## Results summary

- **Symbols audited:** 80+ distinct symbols/symbol families (complete ledger in MASTER_SYMBOL_LEDGER.md); all occurrences of all load-bearing symbols individually checked.
- **Meaning stability:** no symbol changes meaning silently within its declared scope. All cross-section reuses are either subscript-separated, font-separated, or (in the flagged cases) recorded in the collision report.
- **Type stability:** two flagged items — σ label→sign-factor (collision report X8) and I_bulk bridge→intrinsic (X6). Both are reconcilable under the manuscript's own number-class/licensing rules but neither reconciliation is stated in-text.
- **Definition-before-use violations:** four substantive (U1, U2, U4, U5 in UNDEFINED_SYMBOLS.md), one trivial (U3).
- **Dimensional status:** fully consistent. Every quantity is dimensionless until §14.2; physical units enter exactly at the calibration display and nowhere earlier. The audit specifically checked every occurrence of ℏ (19 lines, §§6 and 8): all are inside explicitly typed bridge clauses; none leaks into an internal derivation. MeV appears only in §14–15 reporting. This is one of the cleanest dimensional disciplines the auditor has seen in a foundational manuscript.
- **Intrinsic/observer boundary:** maintained everywhere except the notational blur at X5/X6 (A#, I_bulk), where the mathematics is fine but the glyphs cross the boundary the prose polices.
- **Symbols in equations but absent from prose:** none found — every displayed symbol is discussed in adjacent prose (a strength of the manuscript's expository style).
- **Symbols in prose but absent from equations:** the internal codenames (S02, C4, T3, P0, lens-calibration identity) — prose-only tokens with no formal referent in the paper (U5).
- **Index discipline (k, K, x, n):** §5 uses k (update rule), K (closed form/live state), x (count arguments of N_tick, u_tick). §5.1 fixes k ≠ event index ≠ physical time, but the k/K/x division of labor is never stated; §7 then uses x for windows and §13.1 reuses x for the phase 2/9 (collision X1). No incorrect statement results; reader load is real.
- **Equation numbering:** the manuscript numbers no equations; all internal references are verbal. Mechanical consequence: this audit cites section+description instead of equation numbers — a journal referee will face the same overhead (see desk-rejection assessment).

## Notable per-occurrence checks (verified against PDF)

| Check | Result |
|---|---|
| every occurrence of m distinguishes active m (=1/(2π), S02 book) from m_base | ✓ §8.6 and §8.8 state the distinction explicitly at the only two points of contact |
| every occurrence of 2/3 typed to its owner (S_flow vs ν(Π_o) vs A#_o vs Koide benchmark) | ✓ §10.3–10.4, §12.1, §15.2 all carry ownership statements |
| N_tick(x) never read as tick count | ✓ warned §5.2 and re-warned §7.1 |
| Ω aliases (Ω_geom, Ω_pack, ω_cell) used per declared roles after §5.2 | ✓ |
| τ (=2π) and lepton-τ subscripts never co-occur in a display | ✓ (X3 remains cosmetic) |
| G role (§7.7) never silently acquires the §3 value 18π | ✓ §7.7 states "used here by role, not by value"; §7.9 boundary reconfirms |
| C4 invariant never used to source the spectral phase | ✓ §10.4 and §12.1 both state the separation; §15.2 restates it for the Koide benchmark |
| electron standard M_e^std occurs only in §§14–15 | ✓ eight occurrences, all downstream of the ratio derivation |
| measured muon/tau values | **zero occurrences anywhere** — confirmed by regex over the full text (no 105.658…, 1776.8/9…, 206.768… other than the paper's own derived outputs; no "PDG"; CODATA cited only for the electron) |
| s_409 occurrences all post-quadratic and middle-only | ✓ 16 occurrences; every application shows (q_min, s_409·q_mid, q_max) |

## Manuscript ↔ EQ-card agreement (symbol level)
See MANUSCRIPT_EQCARD_NOTATION_DIFF.md. No disagreement that changes a value or a claim; systematic λ↔Λ glyph difference and several card-side decorations (superscript "scr") that the manuscript drops.
