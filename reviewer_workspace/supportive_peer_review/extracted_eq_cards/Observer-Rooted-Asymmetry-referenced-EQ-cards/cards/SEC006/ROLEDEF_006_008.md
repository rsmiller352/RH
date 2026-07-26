---
id: ROLEDEF_006_008
publication_dependencies: ["DEF_006_005","GUARD_006_001","THM_002_014","THM_006_007"]
---

# φ_rel — the S05 relative-coherence-phase typed reading (role card): the relative coherence-phase is the reading 2π·g_Φ mod 2π (the action-gap g_Φ, DEF_006_005, in 2π closure units); only RELATIVE phase is contentful (the phase is a gap, no absolute); the 2π closure unit τ is CONSUMED (THM_002_014), not owned; the closure count I = ⌊|g_Φ|⌋ is THM_006_007's; the discrete ±1 non-reduction is GUARD_006_001's (OB-D). Mints no glyph (GATE-5); φ_rel is card-local notation

## 0) Governance & Scope Lock

Role-definition card (ROLEDEF): TYPES the S05 **relative-coherence-phase reading**. The content: the
**relative coherence-phase** between two histories is the reading **2π·g_Φ** (the action-gap g_Φ,
DEF_006_005, in 2π closure units), defined **mod 2π**; **only RELATIVE phase is contentful** (the phase
is a gap/difference, g_Φ orientation × magnitude, P3; an absolute offset is unobservable); the **2π
closure unit is τ = 2π**, **CONSUMED** from S02 (THM_002_014), never owned/re-derived here; the **closure
count is I = ⌊|g_Φ|⌋** (THM_006_007 — named, not re-proved; ℤ≥1, the sub-unit case the record-absent
predicate, never I = 0, GUARD_006_006). **GATE-5: NO standalone phase glyph** (2π·g_Φ is notation; φ_rel
card-local). **OB-D:** whether the discrete ±1 (σ) reduces to the continuous phase is deferred to S06 —
routed to **GUARD_006_001** (clause 2). Banned: any new registry glyph / φ_rel-as-registry-symbol; any
absolute-phase object; any S05 discrete-reduction; any re-derivation of τ=2π or the floor count; any
I=0; any e^{iτ} BRIDGE form; any decimal (P8). Depends on DEF_006_005, THM_002_014, THM_006_007,
GUARD_006_001. Layer ceiling S05. Cited as the S05 relative-phase reading and nothing else (TD-011).

**[DRAFT marker, D-064 card 7/13 Phase 0]:** drafted into draft_eq_spine for the RSM gate; nothing in
eq_spine is touched, no glyph minted. Certifies NOTHING — pending witness → verifier → drift → RSM gate.
On promotion, CONV_S05_009 is superseded to this card (Phase 3, last).

## 1) Plain language

S05's relative-phase reading says how the count we built relates to **phase** — the cyclic, wrap-around
character of distinguishability. Between two histories we already have the action-gap g_Φ. Multiply it by
one full turn, 2π, and you have the **relative coherence-phase** between them: 2π·g_Φ. Because g_Φ is a
*gap* — a difference, orientation × magnitude, never an absolute amount — the phase is automatically
**relative**: there is no "absolute phase" of a single history, and shifting everything by a constant
offset changes nothing observable. A full turn is **2π**, and this card does **not** re-invent that — it
is the closure value the book already earned (τ = 2π, THM_002_014); we just **read** with it. The number
of *whole turns* the phase has wrapped is exactly the floor count **I = ⌊|g_Φ|⌋** (THM_006_007's, named
here). This card **types that reading** — it mints no new symbol (2π·g_Φ is just notation), proves no
theorem, and leaves the discrete-±1 question (is the sign a shadow of this phase?) to S06 (GUARD_006_001).

## 2) Statement (the typed reading)

> **(The relative-coherence-phase reading.)** For two histories with action-gap g_Φ (DEF_006_005,
> orientation × magnitude), the **relative coherence-phase** is the reading
> $$\varphi_{\text{rel}} \;:=\; 2\pi \cdot g_\Phi \pmod{2\pi},$$
> the gap in 2π closure units, defined **mod 2π**. 2π·g_Φ is **notation** over the promoted g_Φ and the
> consumed closure value 2π — **no new registry glyph** (GATE-5); φ_rel is a card-local label.
>
> **(Only relative phase is contentful.)** The coherence-phase is a **gap/difference** (g_Φ); the
> framework has **no absolute phase**. An absolute offset (a uniform constant added to every phase) shifts
> **no** relative phase and changes **no** resolved content (the closure count I) — it is **unobservable**.
> This is a role-reading fact: the phase is *read as a gap*, so only its relative value carries content.
>
> **(The 2π closure unit — consumed, not owned.)** The full-turn closure value is **τ = 2π** (THM_002_014;
> DEF_003_002 (the active S02 τ label) / ROLEDEF_003_007 (the τ_R reading)). This reading **CONSUMES** it; it never
> re-derives or re-owns it.
>
> **(The closure count — named, THM_006_007's.)** The number of completed 2π closures of the phase is the
> floor count $$I \;=\; \big\lfloor |g_\Phi| \big\rfloor \qquad (\text{THM\_S05\_007}),$$ each completed 2π
> closure one completed unit of distinguishability (ℤ≥1 for ≥1 closure; the sub-unit case the record-absent
> predicate, never I = 0, GUARD_006_006). This card NAMES the count, does not re-prove it.
>
> **(The discrete ±1 — deferred to S06, OB-D → GUARD_006_001.)** S05 uses ONLY this continuous phase.
> Whether the discrete ±1 orientation (σ, DEF_002_002) is a quotient/limit/reduction/derivation of the
> continuous coherence-phase is an **S06 obligation (OB-D)**, NOT decided here — routed to **GUARD_006_001**
> (clause 2).

## 3) Input contract (GR-1)

Objects: the action-gap g_Φ (DEF_006_005); the relative coherence-phase 2π·g_Φ mod 2π (notation,
card-local — no registry glyph); τ = 2π (THM_002_014, the closure unit consumed; DEF_003_002 /
ROLEDEF_003_007 the active readings, named); π (registry, symbolic, P8); the closure count I = ⌊|g_Φ|⌋
(THM_006_007, named); σ (the discrete orientation, DEF_002_002 — NAMED as the OB-D-deferred object, not
used). Domains: pairs of histories with their action-gaps; phase read mod 2π. Quantifiers: universal over
history pairs (the relative phase + closure count); the absolute-offset invariance universal over offsets.
Finite-N surface: the deformation case (τ ↦ π_L(N), the ROLEDEF_003_007 clause-3 model, named not
consumed). Limit: π_L(N) → π (continuum recovery, named).

## 4) Justification (ROLEDEF; the facts named, not re-proved)

The card types one reading and its disciplines; each grounding fact is owned upstream and named, none
newly derived.

**(Only relative phase is contentful.)** The coherence-phase here is *read as* 2π times the action-gap
g_Φ — a gap (orientation × magnitude, DEF_006_005), a relation between two histories, not an absolute
property of one. So "only relative phase is contentful" is **structural to the reading**, not a postulate:
there is no absolute-phase object, and an absolute offset is invisible because it shifts no g_Φ. This
grounds (without importing) the corpus's "only relative phase is physical" (gen2 THM_S12, the discrete
miniature deferred to S06).

**(Consume-not-own.)** τ = 2π is the earned full-return closure value (THM_002_014). This reading consumes
it for the mod-2π closure; it never re-derives or re-owns it (TD-012/TD-021 — one closure value, owned at
S01/S02, read here). The active S02 readings (DEF_003_002 (the active S02 τ label), the τ_R role ROLEDEF_003_007) are the consume
source.

**(The closure count is named.)** Each completed 2π closure of the phase is one whole turn, i.e. one
completed unit of distinguishability — so the count is I = ⌊|g_Φ|⌋, **THM_006_007's theorem**, named here
as the reading's closure count, not re-proved. The phase-closure reading and the account-completion count
are the **same count**, two readings.

**Why ROLEDEF, not CONV/DEF/THM.** It types a *reading* over owned objects (the τ_R / ROLEDEF_003_007
shape): it chooses among no alternatives (not a convention's declared choice), mints no glyph and defines
no object (not a DEF), and proves nothing (the facts are theorem/GUARD-owned — not a THM/LEM). The
surviving content is role-typing of the relative-phase reading.

## 5) Scope & non-overclaim

Types the relative-coherence-phase reading (2π·g_Φ mod 2π), the only-relative discipline, the consume-not-own
reading, and names the closure count (I = ⌊|g_Φ|⌋). Does NOT: re-derive τ = 2π or re-prove the floor count
(THM_002_014 / THM_006_007); define the aperture object A_Φ (DEF_006_010) or the e^{iτ} BRIDGE form
(S05.10); decide the discrete↔continuous reduction (S06/OB-D → GUARD_006_001); admit an absolute phase
(only relative contentful); admit I = 0 (GUARD_006_006); mint a phase glyph (GATE-5 — 2π·g_Φ notation,
φ_rel card-local). Guard references: GUARD_006_006 (no I = 0), GUARD_006_001 (two-phase / OB-D), P3 (g_Φ a
gap), TD-023 (the OB-D deferral), GUARD_001_006 (layer ceiling).

## 6) Per-symbol accounting

Local (notation, NOT registry symbols): the relative coherence-phase 2π·g_Φ mod 2π (card-local notation
over g_Φ + 2π — GATE-5, no glyph minted); φ_rel (the same, a card-local label — NOT a registry symbol).
Imported / consumed: the action-gap g_Φ ← DEF_006_005; τ = 2π ← THM_002_014 (the closure unit, consumed);
the closure count I ← THM_006_007 (named); the two-phase distinctness / OB-D ← GUARD_006_001; π ← registry
(symbolic, P8). Named (NOT consumed): σ ← DEF_002_002 (the discrete orientation, the OB-D-deferred object);
DEF_003_002 / ROLEDEF_003_007 (the active S02 τ readings, the consume source); π_L(N) (the named
deformation model, TD-020). **No new registry glyph (GATE-5).** Undeclared: none.

## 7) Verification (witness — exact-symbolic, symbolic π; migrated from CONV_S05_009's witness, reframed as role-reading consistency)

Witness `tools/verifications/S05/ROLEDEF_S05_015_witness.py`:

1. **The relative phase mod 2π (value-level, symbolic π).** φ_rel = 2π·g_Φ well-defined mod 2π (adding
   whole 2π turns leaves the residue invariant); the closure value is exactly 2π (symbolic, CONSUMED from
   THM_002_014, not re-derived).
2. **Only relative phase is contentful — role-reading consistency (LOAD-BEARING).** An absolute offset added
   to every history's phase leaves every RELATIVE phase (2π·g_Φ) AND the closure count I INVARIANT — the
   reading of the phase *as a gap* is gauge-invariant; the absolute phase is offset-sensitive (no content).
   (Not a theorem proof — a consistency of the typed reading.)
3. **The closure count I = ⌊|g_Φ|⌋ ↔ completed 2π closures (THM_006_007, named).** Independently count the
   completed 2π turns of φ = 2π·g_Φ and cross-check against ⌊|g_Φ|⌋ (each turn one unit); ℤ≥1; the sub-unit
   case the record-absent predicate, never I = 0.
4. **No discrete-±1 reduction at S05 + representation audit.** A "discrete ±1 (σ) = reduction of the
   continuous phase" claim at S05 is REJECTED (OB-D → GUARD_006_001; admitted only at S06, license-driven);
   exactly ZERO new glyphs (φ_rel notation, GATE-5); no decimal (symbolic π, P8); no e^{iτ} complex form.
5. **Can-fail (`--corrupt` / `--mode {A,B,C,D}`), REQUIRED — one mode, one check (TD-035).** Bare `--corrupt`
   = Mode A (the load-bearing only-relative). **A** (absolute phase contentful): an offset changes a relative
   phase / I → check 2 fails (F-S05cl-1). **B** (discrete reduction at S05): admit it → check 4 fails
   (F-S05cl-2, the GUARD_006_001 teeth). **C** (τ-only — τ re-derived): posit τ ≠ 2π → check 1 fails; check 3
   holds (the count reads k ≤ |g_Φ|, TAU cancels — scale-invariant) (F-S05cl-3). **D** (count-only — I
   decoupled): a spurious extra 2π turn with τ = 2π untouched → check 3 fails; check 1 holds (F-S05cl-3).

A pass certifies the reading's consistency (mod-2π + only-relative + the named closure count + the OB-D
deferral) — a role-reading consistency, NOT a truth-claim (the facts are theorem/GUARD-owned). Modes A and B
are load-bearing.

## 8) Falsifiers

As in frontmatter — **F-S05cl-1** (absolute phase contentful — the only-relative one, Mode A, load-bearing),
**F-S05cl-2** (discrete-±1 reduction claimed at S05 — the OB-D one, Mode B, load-bearing), **F-S05cl-3** (τ
re-derived / closure-count broken — Modes C (τ-only) / D (count-only), split one-mode-one-check per TD-035). The reading can lose at the only-relative gauge-invariance
(F-S05cl-1), the OB-D deferral (F-S05cl-2), or the consume-not-own + closure↔count correspondence
(F-S05cl-3). Loss handling per D-042: the phase-as-gap reading / the OB-D deferral / the consume-not-own
held true through diagnosis; a violating construction is the suspect. Reopen: an RSM re-ruling, or the S06
obligation OB-D resolving the discrete↔continuous relationship (deferred, not broken), or a proved
contextual deformation of the closure value (τ ↦ π_L(N), the ROLEDEF_003_007 clause-3 case — anticipated).

## 9) Notes

**(i) GATE-5 resolved — no phase glyph (R15-17-conservative; RSM care item).** GUARD_006_001 reserved the
continuous coherence-phase as a typed role distinct from σ, deferring its glyph. This reading realizes it as
the **notation 2π·g_Φ** (the promoted gap × the consumed closure value), NOT a new registry glyph; φ_rel is a
card-local label. **(ii) Consume-not-own — the closure value is S02's (RSM care item).** τ = 2π is earned at
THM_002_014; this reading consumes it, never re-derives/re-owns it (TD-012/TD-021). The floor count I is
THM_006_007's, named not re-proved. **(iii) The S06 seam (OB-D) — routed to GUARD_006_001.** Whether the
discrete ±1 (σ) is a quotient/limit of the continuous phase is OB-D, an S06 obligation; the fence is
GUARD_006_001's (clause 2). The e^{iτ} BRIDGE form (S05.10) and the aperture object A_Φ (DEF_006_010) are not
grounded here. **(iv) Supersession provenance (D-064 card 7/13, the LAST).** This ROLEDEF supersedes
CONV_S05_009. The reading-duty re-homes here; the facts stay owned (g_Φ → DEF_006_005; τ → THM_002_014; I →
THM_006_007; no-zero → GUARD_006_006; two-phase/OB-D → GUARD_006_001). Value/name/shape-preserving: the
reading, the closure count, all disciplines unchanged — only type CONV→ROLEDEF.
