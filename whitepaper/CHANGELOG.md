# The Reasoning Corpus Whitepaper Changelog

This changelog preserves the public release history of *The Reasoning Corpus: Preserving Intellectual Provenance in the Age of AI*.

The repository should retain each published version rather than replacing earlier releases. The purpose is to preserve chronology, provenance, and the visible development of the whitepaper.

## Version 1.2 - October 7, 2026

### Release status
Current published revision.

### Major additions
- Added **Retrieval Surface Variability**.
- Documented **Retrieval Divergence vs. Reasoning Convergence**.
- Added **Preservation Does Not Guarantee Recovery**.
- Introduced the retrieval hierarchy:

  `Memory -> Corpus retrieval -> Interpretation`

- Distinguished preservation, synchronization, indexing, retrieval, and interpretation as separate operational stages.
- Added the observation that an artifact may be preserved and indexed yet still fail to be recovered through a natural-language description.
- Added the operational principle that when a user clearly refers to a prior artifact, conversational recall should be followed by a corpus search before reconstruction is treated as evidence.
- Expanded the Key Findings and Conclusion to reflect the new retrieval observations.

### Evidence basis
Version 1.2 draws from preserved mobile-versus-desktop Copilot retrieval experiments and the later failure to recover the indexed experiment handoff by description.

The supported observation is narrow:

> Mobile and desktop Copilot sometimes retrieved different evidence sets, while their higher-level conclusions sometimes converged.

Version 1.2 does not claim that the two interfaces use different underlying reasoning systems, nor does it establish that one interface is generally superior.

### Preserved artifact
- `The_Reasoning_Corpus_v1.2.pdf`

---

## Version 1.1 - October 3, 2026

### Release status
Preserved substantive revision.

### Major additions
- Added **Timestamp Authority and Date-Boundary Integrity**.
- Distinguished conversation chronology from artifact chronology.
- Established the artifact creation timestamp as authoritative for the handoff filename and internal metadata.
- Added **Chronological Integrity** as a core design principle.
- Added **Date-Boundary Drift** as a distinct observed failure mode.
- Expanded the conclusion and key findings to preserve the distinction among event chronology, conversation chronology, and artifact chronology.
- Preserved version 1.0 rather than silently replacing it.

### Key principle
> Provenance fields describe the artifact, not the topic.

### Preserved artifact
- `The_Reasoning_Corpus_v1.1.pdf`

---

## Version 1.0 - October 1, 2026

### Release status
Initial public release.

### Major contents
- Defined the Reasoning Corpus as a personal reasoning-preservation system.
- Described the six-layer architecture:
  1. Primary Reasoning
  2. Structured Handoffs
  3. Voice-First Journaling
  4. Canonical Preservation Format
  5. Repository Preservation
  6. Retrieval
- Established Markdown as the canonical textual preservation format.
- Documented the OneDrive repository structure and direct-ingestion workflow.
- Defined the initial chat-handoff and journal-entry formats.
- Introduced record fidelity, intellectual provenance, human-readable authority, lightweight metadata, and retrieval over recall.
- Documented early operational challenges including downloadability drift, naming drift, metadata drift, indexing delay, instruction-retention variability, and survivor bias.
- Introduced the observation that repository retrieval sometimes restored documented context before conversational continuity reproduced it.

### Central finding
> Reliable AI continuity does not necessarily reside inside the AI. It can emerge from faithful records that remain available for retrieval.

### Preserved artifact
- `The_Reasoning_Corpus_v1.0.pdf`

---

## Versioning policy

- Published versions remain preserved as separate artifacts.
- A substantive revision receives a new version number.
- Earlier versions are not overwritten merely because a later version exists.
- Corrections, additions, and changed interpretations remain visible through the version history.
- Release dates describe the published artifact, not necessarily the date of every event discussed within it.
- The changelog records major differences. It is not a substitute for the full whitepapers or their supporting corpus records.

## Current whitepaper directory

```text
Whitepaper/
├── CHANGELOG.md
├── The_Reasoning_Corpus_v1.0.pdf
├── The_Reasoning_Corpus_v1.1.pdf
└── The_Reasoning_Corpus_v1.2.pdf
```
