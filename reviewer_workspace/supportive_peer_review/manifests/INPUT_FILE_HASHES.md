# Input File Hashes

SHA-256 hashes of every supplied input file, computed at intake and never recomputed against modified copies. Supplied inputs in `intake/` are treated as read-only source material; they are never edited.

**Intake date:** 2026-07-26

| File | SHA-256 | Size (bytes) | Received |
|---|---|---|---|
| `intake/ObserverRootedAsymmetry.pdf` | `11f20aa4e3e47cfdf66748b0780b85a78920a45670c420e8b786584287db7692` | 904,244 | 2026-07-26 |
| `intake/ObserverRootedAsymmetryreferencedEQcards.zip` | `b528c51b6ff2f6cb9d94bb96d5b7e1c6cd4d201b5a5d4129cda7415bafdafba5` | 890,668 | 2026-07-26 |

## Manuscript facts at intake

| Property | Value |
|---|---|
| Title (PDF metadata) | Observer-Rooted Asymmetry |
| Subject (PDF metadata) | A Closure-First Derivation of Charged-Lepton Mass Ratios with Independent Koide Validation |
| Producer | pdfTeX-1.40.29 (LaTeX with hyperref) |
| Pages | 56 |
| Extracted word count (approx.) | 21,098 |

## ZIP package facts at intake

| Property | Value |
|---|---|
| Files in archive | 152 (148 EQ cards + `README.md`, `PACKAGE_MANIFEST.json`, `MANUSCRIPT_CARD_REFERENCE_MAP.json`, `FILE_HASHES.sha256`) |
| Internal integrity check | All files verified against the package's own `FILE_HASHES.sha256` — zero mismatches |
| Package self-description | 148 unique active publication EQ cards referenced by the release-facing traceability records of `PUB-MANUSCRIPT-2026-07-26-006` |

## Intake observation (recorded, non-blocking)

The package `README.md` records a "Manuscript SHA-256" of `3a19c90b71b526a9567cddb8935c2dd0e5a4c70ea9521b80a8dabc59394584f7`, which does not match the hash of the supplied PDF (`11f20aa4…`). The charitable and most probable reading is that the package hash refers to the manuscript *source* file (e.g., LaTeX/Markdown) rather than the rendered PDF, which is a different byte stream by nature. This is recorded here for traceability. Correspondence between the supplied PDF and the card set will be established substantively during review (card IDs cited in the PDF versus cards present in the package), which is the check that actually matters for the reader.
