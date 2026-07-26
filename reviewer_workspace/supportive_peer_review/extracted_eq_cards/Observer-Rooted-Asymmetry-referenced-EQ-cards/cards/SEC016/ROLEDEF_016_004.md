---
id: ROLEDEF_016_004
publication_dependencies: ["THM_016_003"]
---

# Downstream Charged-Lepton Names for the Intrinsic Rank Triple

## 0. Governance and one role-definition claim

This governed formal card records one source-governed downstream reporting
definition.
It does not derive a particle identity and does not strengthen
`THM_016_003`.

Its one claim is the definition of a bijective naming map from the invariant
rank set to three charged-lepton reporting roles.

## 1. Source and target types

Let

\[
\mathcal K_{\rm rank}
=
\{\min,\operatorname{mid},\max\}
\]

be the presentation-invariant rank set of `THM_016_003`, and let

\[
\mathcal L_{\rm report}
=
\{e,\mu,\tau\}
\]

be a set of downstream reporting-role labels.

The target labels are not intrinsic sector indices and are not experimental
measurements.

## 2. Role definition

Define

\[
\boxed{
\operatorname{LeptonRole}:
\mathcal K_{\rm rank}
\longrightarrow
\mathcal L_{\rm report}
}
\]

by

\[
\boxed{
\operatorname{LeptonRole}(\min)=e,
\qquad
\operatorname{LeptonRole}(\operatorname{mid})=\mu,
\qquad
\operatorname{LeptonRole}(\max)=\tau.
}
\]

The three images are distinct and exhaust the three target labels, so this is
a bijection by inspection.

This card’s disposition is

```text
DEFINED-DOWNSTREAM-RANK-ROLE
```

as content authority. Promotion installation still requires the later
card-by-card approval boundary.

## 3. What the definition does not say

The definition does not claim:

- that a theorem derived these names;
- that any fixed sector index is intrinsically one named role;
- that a laboratory mass was used to sort or select the ranks;
- that observer depth generates an intrinsic support;
- that the withdrawn `LEM_010_012` is restored;
- that a name changes an amplitude, support, ratio, or coefficient; or
- that an empirical comparison has been performed.

For any permitted presentation permutation, the displayed index of a rank may
change while its rank and downstream role remain unchanged.

## 4. Role recovery and invariance

Because the source rank values are strictly ordered, each support record
recovers its rank by comparison with the unordered triple. Applying
\(\operatorname{LeptonRole}\) then recovers the downstream label. No sector
index is needed.

The inverse role dictionary is

\[
\operatorname{LeptonRole}^{-1}(e)=\min,
\qquad
\operatorname{LeptonRole}^{-1}(\mu)=\operatorname{mid},
\qquad
\operatorname{LeptonRole}^{-1}(\tau)=\max.
\]

This inverse is role metadata only; it does not invert a physical
measurement.

## 5. Claim taxonomy and authority

| Field | Disposition |
|---|---|
| claim category | role definition |
| mathematical derivation | not claimed |
| source basis | explicit downstream-reporting instruction at `SRC_000219:L500-L509` and corrective scope at `SRC_000228:L55-L60` |
| value slots | consumes already-proved rank values; introduces none |
| empirical input | none |
| particle identity strength | downstream reporting role only |
| withdrawn source | prohibited |

This record is downstream naming metadata, not a mathematical transformation
in the mass derivation. Every numerical and rank-valued step is already
forced before this map is applied; this map supplies no quantity and modifies
none.

## 6. Exact source map

| Role content | Exact Source Card range |
|---|---|
| retain theorem as minimum/middle/maximum | `SRC_000219:L500-L506` |
| attach names through an explicit downstream role | `SRC_000219:L508-L509` |
| keep this role outside load-bearing mathematics | `SRC_000228:L55-L60,L112-L117` |

## 7. Falsifiers and corrupt modes

The role definition fails if:

1. two ranks receive the same label;
2. a fixed presentation sector replaces a rank;
3. a measured value selects the map;
4. the role is described as theorem-derived;
5. `LEM_010_012` is used as proof ground; or
6. the role changes an intrinsic value.

The durable witness rejects each corruption.
`PROMOTED-BY-GOVERNED-TRANSACTION`.
