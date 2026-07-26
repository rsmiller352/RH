# ISSUE-007 — No measured muon/tau comparison anywhere in the manuscript

**Severity: Level 3 (persuasiveness risk).** Classification: PERSUASIVENESS_RISK.

## Exact location
§14.3 (diagnostic outputs displayed; no measured values quoted); global (mechanical scan confirms zero occurrences of any measured muon/tau value or "PDG").

## Exact claim under review
Not a stated claim — a structured omission: the paper derives r_μ = 206.768282732… and M_τ^out = 1776.985 MeV and never tells the reader how these compare with measurement. Reviewer-established facts (30-digit computation; reference values from CODATA 2022): the derived r_μ lies **within the experimental uncertainty** of the measured m_μ/m_e = 206.7682827(46) (difference +3.2×10⁻⁸); the τ output lies ≈0.6σ above the current measured τ mass (1776.93 ± 0.09 MeV).

## Context examined
- *Local/section:* §14.3's "diagnostic" labeling; §14's closing scope paragraph; §15.0's ordering statement.
- *Manuscript:* the input-hygiene discipline (no measured value may appear upstream); §15 performing a *post-derivation* comparison for Koide — demonstrating that afterward-comparison is admissible within the paper's own rules.
- *Cards:* BRIDGE_016_007 §6 ("Any later comparison is therefore a post-data-exposure consistency comparison, not a new blind held-out prediction") — the card explicitly anticipates such comparisons.
- *Charitable reconstruction:* the omission is deliberate input hygiene: quoting measured values anywhere might blur the no-input claim, and the authors may prefer readers to perform the check.

## Why the charitable interpretation is insufficient
The hygiene motive is fully served by *placement and typing*, not by omission — as the paper itself proves in §15, where an external benchmark is quoted, compared against, and typed ("independent downstream consistency check") without contaminating anything. The present configuration has the paper's least favorable property: the strongest empirical fact (sub-uncertainty muon-ratio agreement) is invisible, while a skeptic's discovery of it *outside* the paper can be framed as "the authors knew and didn't say." Editors triage partly on stated outcomes; referees check comparisons first. Additionally (CI-14), any comparison requires one sentence on scheme/scale (the derived ratios are compared against pole-mass-like CODATA/PDG values; the m_μ/m_e ratio's scheme stability makes the sub-ppm statement meaningful) — currently also absent because no comparison exists.

## Reader consequence
The paper under-reports its own result; the reader must fetch and compute externally to learn what the derivation achieved; the τ statement (consistent, parameter-free beyond the electron anchor) is likewise never made.

## Smallest sufficient repair
A short passage or small table at the end of §14.3, typed with exactly §15's status language, e.g.: *"For post-derivation comparison only (no measured muon or tau value enters any construction above): the measured m_μ/m_e = 206.768 2827(46) [CODATA 2022]; the derived value lies within the stated experimental uncertainty. The measured τ mass, 1776.93(9) MeV [ref], lies ≈0.6 experimental standard deviations below the derived 1776.985 MeV. Both comparisons are post-data-exposure consistency statements in the sense of §15, not blind predictions; the derived ratios are compared here directly with the measured mass ratios, whose scheme dependence is negligible at the stated precision."* Plus one reference for the τ value (feeds ISSUE-002's reference repair).
