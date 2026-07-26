---
id: ROLEDEF_005_018
publication_dependencies: ["DEF_002_004","DEF_005_007","DEF_005_012","THM_004_018","THM_005_009","THM_005_010","THM_005_015","THM_005_016","THM_005_017"]
---

# The runtime event-role discipline — tick (base runtime event, per-ω_cell increment), escapement (the residual-threshold crossing → one cell), the cell-event role (REF(λ), THM_004_018); the FROZEN N_tick glyph bound to escapement-count; the unified base index and the k≠n≠t (base/escapement/physical-time) index roles; not-a-rate. Typed event-roles over already-promoted runtime facts; mints no math glyph, proves no theorem

## 0) Governance & Scope Lock

Role-definition card (ROLEDEF): types the S04 runtime **event-roles** and reconciles historical
wording; derives nothing new, proves no theorem. Two distinct runtime events: a **tick** (the base
event — one per running cycle, each advancing the residual register by `ω_cell = Ω`, Ω < 1) and an
**escapement** (the residual-threshold crossing a tick causes **only when** the residual reaches a
unit, `THM_005_009`; **not every tick**). One escapement → one **cell** (the `REF(λ)` object,
`THM_004_018`) — the **one-cell-per-escapement fact is `THM_005_020`'s** (growth realization; named
here, not proved). The frozen glyph **`N_tick`** (RSM — no rename) is bound to **escapement-count**
(`N_tick(x)=⌊x·Ω⌋` counts crossings, `THM_005_010`/`THM_005_016`). The promoted cards **invert**
"tick" (they call the crossing a "tick"); they stay **byte-for-byte** (amendment-lock), and this card
carries the **reconcile-without-editing** map (their "tick" = escapement; their "cycle" = tick). The
base index is **unified**. Banned: editing any promoted card; renaming `N_tick`; proving the
growth-realization fact (THM_005_020's); any "rate"/time reading (TD-019/TD-003); any new math glyph;
any located-site/multi-cell content; any decimal for Ω (P8). Depends on `THM_005_010`, `THM_005_009`,
`THM_005_015`/`011`/`012`, `DEF_005_007`, `DEF_005_012`, `DEF_002_004`, `THM_004_018` (all upstream).
`THM_005_020` is a **named forward-pointer, NOT a dep-edge** (it consumes this card — acyclic). Layer
ceiling S04. Cited as the tick/escapement/cell event-role discipline and nothing else (TD-011).

**[DRAFT marker, D-064 card 5/13 Phase 0]:** drafted into `draft_eq_spine/` for the gauntlet; nothing
in `eq_spine/` is touched, no promoted card is edited, `N_tick` is not renamed, `symbols.yaml` is not
edited (event-role ownership moves at Phase 2). Certifies NOTHING — pending witness → verifier → drift
→ RSM gate. On promotion CONV_S04_024 is superseded to this card (Phase 3, last).

## 1) Plain language

The running machinery advances in small steps. Call each step a **tick**: every tick adds the same
small share `ω_cell = Ω` (Ω < 1) to the running residual. Most ticks just nudge it along. But the
moment a tick pushes the residual **across a whole unit**, that crossing is a different event — an
**escapement** — and it is the escapement that **completes a unit of existence and creates one new
cell**. A tick can *cause* an escapement, but **not every tick causes one** — only the one that
crosses. Because each tick adds only `Ω ≈` a quarter-ish, an escapement happens roughly every 3–4
ticks, varying with the residual (the `{3,4}` staircase). **One cell per escapement — never one cell
per tick** (the *proven* growth-realization fact is `THM_005_020`'s; this card only types the roles).

The existing cards proved all of this but used **"tick" for the crossing** (`THM_005_010`: "a tick
fires ⟺ it crosses the unit threshold") and **"cycle"** for the base step — the opposite of the names
fixed here. We do **not** edit those cards (locked); we record the **map**: a promoted **"tick"** means
our **escapement**; a promoted **"cycle"** means our **tick**. The count glyph **`N_tick`** is kept as
a frozen historical name — and we state what it counts: **escapements (crossings), not base ticks**.
Fixing tick / escapement / cell as registered typed roles (and unifying the base index) lets the
validator/drift checks catch any future "escapement tick" automatically — one term, one meaning.

## 2) Statement (the event-roles, typed once)

> **(tick — the base runtime event.)** A **tick** is the base runtime event: one per running cycle of
> the residual register, each advancing it by `ω_cell = Ω` (`DEF_005_007`; Ω < 1, `DEF_004_012`). Its
> index is the unified base index `k` (clause 5). *(In the promoted cards this base event is called
> "cycle"; clause 6.)*
>
> **(escapement — the residual-threshold crossing.)** An **escapement** is the event a tick causes
> **iff** the updated residual crosses the unit threshold: `S_res(k) ⊕ ω_cell ⪰ 1` (`THM_005_010`;
> equivalently `R_acc ⪰ 1`, `THM_005_009` — a completed unit is FORCED). **Not every tick is an
> escapement.** Each escapement is one forced ι_or posting (`ΔI = 1`, `THM_005_010`/`THM_005_009`).
> *(In the promoted cards this crossing is called a "tick"; clause 6.)*
>
> **(cell — the realization target.)** A **cell** is the `REF(λ)` object (`THM_004_018`; the `M_cell`
> realization target) created at each escapement — the +1 co-end of the transfer (`DEF_002_004` §9).
>
> **(1 — one cell per escapement; never per tick — the fact is `THM_005_020`'s.)** The cell↔escapement
> relation is a **count-binding**: one cell-role per escapement-role event. The **proven fact** that
> each escapement forces exactly one (located, contiguous) cell — the **growth realization** — is
> **`THM_005_020`'s** (named/consumed here, **not proved**; forward-pointer, no dep-edge). It is
> **not** one cell per tick, and **not** a "rate" (no physical time; TD-019).
>
> **(2 — tick ≠ escapement, the load-bearing distinction.)** A tick and an escapement are distinct
> typed events; a tick causes an escapement **only** when the residual crosses a unit. No reading may
> treat every tick as an escapement, or use "escapement" for the base tick. (The discipline whose
> absence produced the "escapement tick" drift.)
>
> **(3 — `N_tick` is a FROZEN glyph bound to escapement-count.)** `N_tick(x) = ⌊x·Ω⌋`
> (`THM_005_010`/`THM_005_016`) is kept **byte-for-byte** as a frozen historical glyph (RSM — no
> rename). Its **semantic role is the count of ESCAPEMENTS (crossings)** over the base ticks — **not**
> the base-tick count. Likewise `T_rt`, and `ΔI=1` = the escapement/cell quantum.
>
> **(4 — the escapement↔tick relation is residual-driven, not fixed, not a rate.)** *How many ticks
> per escapement* is the **residual-driven** `{3,4}` staircase (`THM_005_017`) / `⌊K·Ω⌋` floor
> (`THM_005_015`) — consumed, never a fixed ratio, never a rate.
>
> **(5 — the indices, unified and reconciled with `DEF_005_012` (k ≠ n ≠ t).)** The **base/tick index**
> is the single glyph **`k`** = the promoted update/cycle index `k`; the promoted `S_res(k)`,
> `N_tick(x)`, `T_rt(K)` are the same base index under historical letters — bound `x ≡ K ≡ k`. The
> **escapement index** is **`n`** = the promoted `DEF_005_012` *"tick index (event)"* (the word "tick"
> there is this card's **escapement**, clause 6). So `DEF_005_012`'s **`k ≠ n ≠ t`** reconciles as:
> **`k` = tick index; `n` = escapement index; `t` = physical time (none, TD-019).** No 4th base-index
> letter; `k` is never labelled "the tick index" bare (that would re-open the overload `DEF_005_012`
> already names `n`).
>
> **(6 — reconcile-without-editing the promoted "tick" (words AND indices).)** Promoted cards stay
> byte-for-byte (amendment-lock). The binding map: a promoted **"tick"** (`THM_005_010`'s crossing;
> `N_tick`; the `{3,4}` "tick gaps"; **`DEF_005_012`'s index `n` = "the tick index (event)"**) = this
> card's **escapement**; a promoted **"cycle"** (and the base index `k`) = this card's **tick**.

tick, escapement, cell are **typed event-roles** (process vocabulary — the rank_I/type-tag precedent),
registered to govern prose and enable drift-detection; **no new math glyph** is introduced. `cell`
names `REF(λ)`, it does not redefine it.

## 3) Input contract (GR-1)

Objects: the residual register `S_res(k)` and per-tick increment `ω_cell = Ω` (`DEF_005_007`/
`DEF_004_012`); the threshold predicate `S_res(k) ⊕ ω_cell ⪰ 1` (`THM_005_010`); the forced posting
`ΔI = 1` (`THM_005_009`); the crossing-count `N_tick(x)=⌊x·Ω⌋` (`THM_005_010`/`THM_005_016`, frozen →
escapement-count); the gap word `{3,4}` (`THM_005_017`); the cell referent `REF(λ)` (`THM_004_018`);
the +1-cell transfer (`DEF_002_004` §9). Named, NOT consumed (forward pointer): the one-cell-per-
escapement / growth-realization fact ← `THM_005_020` (its theorem, not a dep-edge). Domains: the
runtime tick family (a bounded tick patch on the witness) and its escapement sub-family. Quantifiers:
the role distinction universal over ticks; `N_tick`'s escapement-count binding universal over `x`.
Finite-N surface: the escapement-per-tick gaps are `{3,4}` at this Ω over a bounded patch. No
rate / no time / no metric.

## 4) Justification (ROLEDEF; the facts named, not re-derived)

The card types four bindings; each grounding fact is owned upstream (or, for growth realization,
downstream at `THM_005_020`) and named, none newly derived.

**(Clause 1/2 — one cell per escapement; tick ≠ escapement.)** `THM_005_010` defines the crossing
event and `THM_005_009` forces exactly one `ΔI=1` at that crossing; since `ω_cell = Ω < 1`
(`DEF_004_012`), most ticks do not cross — the escapement is a strict sub-event of the tick, and the
cell↔tick map is not one-to-one (the `{3,4}` staircase, `THM_005_017`). The **proven** one-cell-per-
escapement (located, contiguous) is `THM_005_020`'s growth realization — **named/consumed here, not
proved** (the RSM care-item; forward-pointer, no dep-edge, acyclic). This card types the roles and the
count-binding; the theorem-home proves the fact.

**(Clause 3 — `N_tick` frozen and bound.)** `N_tick(x)=⌊x·Ω⌋` is the count of crossings over `x` base
ticks — under the adopted vocabulary, the **escapement-count**. RSM ruled keep the glyph frozen and
bind its role — the `ROLEDEF_003_007` pattern (a shared name kept, its role made explicit,
reconcile-without-editing).

**(Clause 4 — residual-driven, not a rate.)** The escapement-per-tick count varies with the residual:
`THM_005_017` proves the gap word is `{3,4}` (⟺ `2√2 < π < 9√2/4`). It is a **count** structure, not a
"rate" — no physical time (`k ≠ n ≠ t`, `DEF_005_012`); calling it a rate is the TD-019/TD-003 hazard.

**(Clause 5/6 — index unification + reconcile-without-editing.)** The base index appears as `k`, `x`,
`K` across promoted cards — one base index under three letters; bound `x ≡ K ≡ k` without editing the
cards. The promoted "tick"(crossing)/"cycle"(base) wording is reconciled by the map (clause 6), never
re-termed in place (amendment-lock).

**Alternatives named and not adopted.** (a) *Rename `N_tick → N_esc`* — rejected (RSM: keep frozen).
(b) *Re-term the promoted cards in place* — rejected (amendment-lock). (c) *A THM/DEF* — rejected:
nothing new is proved (the facts live at `THM_S04_006/010/011/012/019` and the growth realization at
`THM_005_020`) and no new object is defined ("cell" = `REF(λ)` named); ROLEDEF with real falsifiers is
the honest tier (TD-011).

## 5) Scope & non-overclaim

Types the tick/escapement/cell event-roles, the one-cell-per-escapement count-binding (the **fact** is
`THM_005_020`'s), the frozen-`N_tick`→escapement-count binding, the residual-driven (non-rate)
escapement↔tick relation, the unified base index, and the reconcile-without-editing map. Does NOT: edit
any promoted card or rename `N_tick`; **prove** the one-cell / growth-realization fact (`THM_005_020`'s);
derive any new result or define any new object ("cell" names `REF(λ)`); state any "rate"/time relation
(TD-019); fix WHERE/WHICH-site a cell realizes or its contiguity (`THM_005_020`); state any multi-cell
composition (`LEM_010_003` OPEN); price any R21 quantity; introduce any new math glyph. Guard references:
amendment-lock (reconcile-without-editing), P9 (one term/one meaning), TD-019/TD-003 (no rate/time),
`DEF_005_012` (k ≠ n ≠ t).

## 6) Per-symbol accounting

OWNED typed event-roles (process vocabulary, not math glyphs — the rank_I/type-tag precedent; ownership
moved here from CONV_S04_024, Phase 2): **tick** (base runtime event), **escapement** (residual-threshold
crossing → one cell), **cell** (the `REF(λ)` object created at each escapement — named, not redefined).
Reconciled / consumed glyphs: `N_tick` (frozen → escapement-count, `THM_005_010`/`THM_005_016`), `ΔI`
(the escapement/cell quantum, `THM_005_009`), `S_res` (the residual register), `ω_cell`/`Ω`
(`DEF_005_007`/`DEF_004_012`), `T_rt` (the runtime crossing-count, `THM_005_015`); the index discipline
`k ≠ n ≠ t` ← `DEF_005_012`. Card-local: the unified base/tick index `k` (= promoted `x`/`K`), the
escapement index `n`, the reconcile map. Named (NOT consumed — forward/precedent): the one-cell /
growth-realization fact ← `THM_005_020` (its theorem, no dep-edge); the +1-cell transfer ← `DEF_002_004`
§9; `ROLEDEF_003_007` (the precedent). **No new math glyph.** Undeclared: none.

## 7) Verification (witness — structural; reads the REAL promoted residual algorithm, TD-030; symbolic Ω/π, P8; migrated from CONV_S04_024's witness)

Witness `tools/verifications/S04/ROLEDEF_S04_035_witness.py`:

1. **tick ≠ escapement (role distinction; LOAD-BEARING).** Model base ticks over a bounded patch (each
   advances `S_res` by `ω_cell = Ω`, symbolic); mark a tick an escapement iff `⌊(k+1)Ω⌋ > ⌊kΩ⌋`
   (`THM_005_010`). Assert ≥1 tick is NOT an escapement (strictly partial); escapements a strict subset.
2. **`N_tick` = escapement-count.** Assert `N_tick(x)=⌊x·Ω⌋` equals the count of escapements on `[0,x]`,
   NOT `x` (the base-tick count); they differ (Ω < 1).
3. **one cell per escapement; residual-driven gaps; no rate.** Assert #cells == #escapements (count
   identity — the fact NAMED at `THM_005_020`); gaps ⊆ `{3,4}` and BOTH occur (vary — not a constant
   ratio / rate); no time/rate object.
4. **index unification / k ≠ n ≠ t.** Assert one base index (`x ≡ K ≡ k`); no 4th letter; the k/n/t
   roles distinct.
5. **Representation audit.** Ω/π symbolic (no Float); the gap-word window `2√2 < π < 9√2/4` symbolic; no
   new math glyph (role-tags).
6. **Can-fail (`--corrupt {A,B,C,D}`), REQUIRED — one mode per falsifier, each flips ONE check (TD-035).**
   **A** (tick = escapement conflated, LOAD-BEARING): drop the threshold gate → check 1 fails (F-tec1).
   **B** (`N_tick := x`, base-tick count): → check 2 fails (F-tec2).
   **C** (one cell per tick / rate): → check 3 fails (F-tec3).
   **D** (index-role drift, k/n/t): a 2nd inconsistent base index → check 4 fails (F-tec4).

A pass certifies the event-role discipline's well-formedness (tick ≠ escapement; `N_tick` =
escapement-count; one cell per escapement with residual-driven `{3,4}` gaps that VARY, not a rate;
unified index). Mode A is the heart (it proves "escapement tick" is rejected). The one-cell fact itself
is `THM_005_020`'s; the witness checks the *count-binding*, not the theorem.

## 8) Falsifiers

As in frontmatter — **F-tec1** (tick = escapement conflated; the load-bearing one, Mode A), **F-tec2**
(`N_tick` mis-bound), **F-tec3** (one-cell-per-escapement broken / per-tick or rate), **F-tec4**
(index-role drift k/n/t). Loss handling per D-042: the promoted facts (`THM_S04_006/010/011/012/019`,
and `THM_005_020`'s growth realization) held; a violating construction (an "escapement tick", an
`N_tick`=base-count read) is the suspect.

## 9) Notes

**(i) Constructive fix of the drift.** The "escapement tick" drift arose because the registry never
locked the event vocabulary ("tick" lived only inside other entries' meanings, "escapement"/"cycle"
unregistered, base index drifting `k`/`x`/`K`). This card registers tick/escapement/cell as typed roles
and unifies the index, so the discipline is mechanical (validator/drift-checkable) — the `ROLEDEF_003_007`
move.

**(ii) `N_tick` stays frozen (RSM ruling).** No rename; clause 3 binds its role (escapement-count). The
consuming promoted cards are untouched; the binding makes their "tick"=crossing reading explicit.

**(iii) The one-cell-per-escapement fact is `THM_005_020`'s (the promoted growth realization).** When
CONV_S04_024 was written, growth realization was "deferred card 2"; it is now the promoted `THM_005_020`,
which CONSUMES this card's vocabulary. This ROLEDEF NAMES `THM_005_020` as the theorem-home for the
one-cell fact (forward-pointer, no dep-edge — `THM_005_020` → this card, acyclic) and does NOT prove it.
The multi-cell Ω-composition (D-030.Q6 / `LEM_010_003` OPEN) remains deferred, consumed by nothing here.

**(iv) Supersession provenance (D-064 card 5/13).** This ROLEDEF supersedes CONV_S04_024. Event-role
ownership (tick, escapement, cell) moves here; the theorem-facts stay at their homes (threshold/posting/
count/staircase → `THM_005_010`/`THM_005_009`/`THM_005_015`/`011`/`012`; growth realization / one cell
per escapement → `THM_005_020`; static cell referent → `THM_004_018`; index / no-physical-time fence →
`DEF_005_012`). Value/name/shape-preserving: the event-roles, the `N_tick` binding, all facts unchanged
— only type CONV→ROLEDEF + ownership + citations.
