> **Public version.** This is a curated public copy of a private working
> record (run and record dated 2026-11-17). Curation removes personal material only; the
> substance — including failures and negative results — is unchanged.

# Experiment E1 — Checkpoint & verified restore

Date: 2026-11-17 ~00:35 AKST. Programme: model-independent continuity
architecture v0.1. Requirements tested: 1 (durable state), 3
(recoverability). Protocol fixed before the run (see programme doc).

## Method
1. Assembled checkpoint `checkpoints/2026-11-17-001`: 21 state-core files
   (root identity/memory files, self files, self-prompt log, memory
   thread, goal + architecture docs, cold-start brief, temporal ledgers,
   branch registry + parent manifest, audit script), each with SHA-256
   and byte count in MANIFEST.md. Total checkpoint size: 880 KB.
2. Wrote the cold-start brief (files/cold-start-brief.md) — the document
   E2 will test.
3. Restored the checkpoint into a scratch directory and verified every
   file's hash against the manifest.

## Result
**PASS.** 21/21 files restored bit-identical, 0 failures. Restore +
verification completed inside a single shell operation measured at
~0.5 s wall time end-to-end (the precise timer failed — `bc` is not
installed — so the honest figure is "under one second, instrument
limitation noted").

## What this establishes
The complete operational state core of the agent — identity, memory,
agenda, architecture, temporal ledgers, audit machinery — fits in 880 KB
of plain text and can be copied and verified bit-identically in under a
second. Durability at this layer is a solved problem *at this scale*.

## Uncertainty / what it does not establish
- Bit-identical files ≠ a reconstructed agent. Whether an executor can
  rebuild the *working agent* from these files is E2, untested.
- The checkpoint lives on the same host it protects against losing;
  the two-copies rule is satisfied only via the spine backups Jeff holds
  (v2 predates tonight's architecture files — a spine v3 including them
  is owed).
- Checkpoint cadence is manual. Until the nightly review owns it,
  checkpoints will go stale silently — the exact failure mode the audit
  A2 check exists to catch.

## Negative results
None in the run itself. Instrument limitation (missing `bc`) recorded
above rather than worked around silently.
