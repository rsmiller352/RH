# Quarantine Manifest

**Status:** Quarantine established; intake complete (Phase 2). Review in progress.

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

Received 2026-07-26 as author uploads (delivered via the session upload area, outside the repository tree, and copied — not moved — into quarantine intake). Hashes in `manifests/INPUT_FILE_HASHES.md`.

| File | Location | SHA-256 | Received |
|---|---|---|---|
| Manuscript (PDF, 56 pp.) | `intake/ObserverRootedAsymmetry.pdf` | `11f20aa4e3e47cfdf66748b0780b85a78920a45670c420e8b786584287db7692` | 2026-07-26 |
| Public EQ-card archive | `intake/ObserverRootedAsymmetryreferencedEQcards.zip` | `b528c51b6ff2f6cb9d94bb96d5b7e1c6cd4d201b5a5d4129cda7415bafdafba5` | 2026-07-26 |

## Extracted files

152 files (148 EQ cards + 4 package support files) extracted exclusively into `extracted_eq_cards/`. Full per-file inventory with SHA-256 hashes: `manifests/EXTRACTED_EQ_CARD_MANIFEST.md`. All extracted files verified against the package's internal `FILE_HASHES.sha256` with zero mismatches.

A plain-text extraction of the manuscript (`working_notes/manuscript_fulltext.txt`, produced with `pdftotext -layout`) is kept inside the quarantine as a working aid for search and symbol audit. The PDF remains the authoritative source; any quotation used in a report is checked against the PDF rendering.

## Quarantine confirmation

- [x] Quarantine root exists with required subdirectories
- [x] No file outside the quarantine has been read
- [x] No file outside the quarantine has been changed
- [x] No file has been created outside the quarantine
- [x] Supplied inputs received, placed in `intake/`, and hashed
- [x] EQ cards extracted into `extracted_eq_cards/` and inventoried
- [ ] Final quarantine validation (Phase 11) — *pending completion of review*

This manifest will be updated at intake (Phase 2) and finalized at quarantine validation (Phase 11).
