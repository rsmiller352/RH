# Electron Calibration Audit

**Target logic to verify:** dimensionless intrinsic ratios → electron-sector identification → one SI-scale calibration → M_μ, M_τ.

## Checklist

| Requirement | Verdict | Evidence |
|---|---|---|
| Electron mass enters exactly once | **PASS** | M_e^std occurs only in §§14.2–15 (8 occurrences, all downstream of the ratio derivation); defined once as the CODATA 2022 mass-energy equivalent with citation [1]. The bridge ℬ is determined pointwise by ratio preservation + this single anchor (§14.2; BRIDGE_016_008). |
| No measured muon/tau value enters the derivation | **PASS** | Mechanical full-text scan: zero occurrences of any measured muon/tau value, "PDG", or non-electron CODATA datum. Card BRIDGE_016_007 §6: "The derivation uses no measured mass and no NIST or PDG value." Discovery-context caveat (post-muon-exposure development of the 409 construction) disclosed in abstract, §14.3, and card — correctly separated from derivational input. |
| Sector assignment derived before calibration | **PASS (as ordering); see note (a)** | Rank ordering 0 < λ_min < λ_mid < λ_max proved by exact inequalities (§12.2) before §14; the naming map (min,mid,max) → (e,μ,τ) is §14.1, explicitly a "downstream naming convention over already derived ranks." |
| Calibration does not alter dimensionless ratios | **PASS** | ℬ(q) = 𝒮_e·q is a single positive scale; §14.2 states rescaling invariance ("leaves the dimensionless ratios, rank ordering, 206, 409, and s_409 unchanged"); LEM_009_005 proves shape invariance for the Koide functional. |
| Units introduced only at the calibration stage | **PASS** | The dimensional-status audit (symbol_audit/SYMBOL_OCCURRENCE_AUDIT.md) found every quantity dimensionless until §14.2; ℏ appears earlier only inside explicitly typed bridge clauses; MeV appears only in §§14–15. Exceptionally clean. |
| Comparison with measured μ/τ presented afterward | **GAP — no comparison is presented at all** | The manuscript never quotes a measured muon or tau mass anywhere. The charter expects the comparison after calibration; the paper omits it entirely. See CI-9: this protects the no-input discipline but hides the paper's strongest empirical fact (derived r_μ inside CODATA uncertainty; τ output ≈0.6σ from current measurement) and leaves the reader to perform the paper's own decisive check. |

## Wording that could invite a "three-mass fit" misreading
Searched for any phrasing that could be quoted as fitting. Findings:
- §14.3's diagnostic decimals printed to 30 places could look assertive, but they are labeled "for numerical diagnosis" and follow the exact symbolic forms — acceptable.
- "the middle construction… was developed after exposure to muon data" (abstract) is the sentence a hostile referee will quote. It is also the sentence that makes the paper honest. The protection it needs is *context*, not removal: the paper should state explicitly (once, near it) that the *published derivation chain* consumes no muon value and that the exposure caveat concerns discovery order — the abstract's phrasing almost does this; §14.3's "Because the 409 construction was developed after exposure to muon data, the middle output is not presented as a new blind held-out prediction" does it well.
- No passage describes or implies adjusting any coefficient toward a measured value. The claim-status ledger found zero fitted quantities.

## Structural observations
(a) The "electron-sector identification" step in the charter's target logic is, in this paper, the naming convention §14.1 **plus** the anchoring choice ℬ(q_e) = ℬ(q_min) = M_e^std. Anchoring the *minimum* rank to the *electron* record is the one place a physical identification is made (see CI-8: the constitutive sentence is missing). The identification is natural (lightest ↔ lightest) and consistent, but the paper should own it as the constitutive step it is.
(b) The calibration chain is invertible with retained records (§14.2's q = ℬ(q)/𝒮_e; BRIDGE_016_008's invertibility clause) — the §9 recovery discipline visibly paying off.

## Verdict
The calibration logic is correctly ordered, single-anchored, ratio-preserving, and communicated clearly. Two repairs: the constitutive-identification sentence (CI-8) and the typed post-derivation measured comparison (CI-9). Nothing found that could sustain a "disguised three-mass fit" description against the actual text.
