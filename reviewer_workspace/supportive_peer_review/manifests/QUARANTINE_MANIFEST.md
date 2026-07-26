# Quarantine Manifest

**Status:** Quarantine established — awaiting intake of manuscript and EQ-card ZIP archive.

## Absolute permitted root

```
ALICE-BOB-FINAL/reviewer_workspace/supportive_peer_review/
```

All reviewer reads, writes, extractions, notes, ledgers, reports, and temporary artifacts are confined to this root. No repository content outside this root is read, searched, hashed, listed, or modified at any point in the review.

## Quarantine establishment record

| Item | Value |
|---|---|
| Quarantine root created | 2026-07-26 |
| Created by | Designated manuscript reviewer session |
| Repository state at establishment | Empty repository — no prior commits, no pre-existing files anywhere in the working tree. The quarantine folder and its contents are the first files in the repository. |
| Files read outside quarantine before establishment | None (only `git status`/`git branch` metadata was consulted to confirm the working branch; no repository file content existed or was read) |
| Files modified outside quarantine | None |
| Files created outside quarantine | None |

## Supplied input files

*None yet.* The manuscript and the public-facing EQ-card ZIP archive have not been supplied. Upon receipt they will be placed in `intake/`, hashed (SHA-256), and recorded below and in `manifests/INPUT_FILE_HASHES.md`.

| File | Location | SHA-256 | Received |
|---|---|---|---|
| — | — | — | — |

## Extracted files

*None yet.* EQ cards will be extracted from the supplied ZIP only into `extracted_eq_cards/` and inventoried in `manifests/EXTRACTED_EQ_CARD_MANIFEST.md`.

## Quarantine confirmation

- [x] Quarantine root exists with required subdirectories
- [x] No file outside the quarantine has been read
- [x] No file outside the quarantine has been changed
- [x] No file has been created outside the quarantine
- [ ] Supplied inputs received, placed in `intake/`, and hashed — *pending upload*
- [ ] EQ cards extracted into `extracted_eq_cards/` and inventoried — *pending upload*
- [ ] Final quarantine validation (Phase 11) — *pending completion of review*

This manifest will be updated at intake (Phase 2) and finalized at quarantine validation (Phase 11).
