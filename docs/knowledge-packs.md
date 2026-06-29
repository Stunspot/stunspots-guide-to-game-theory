# Knowledge Packs — Stunspot's Guide to Game Theory

This repository separates **navigation** from **corpus**.

- `docs/` contains GitHub Pages navigation and usage guidance.
- `knowledge-packs/by-report/` contains the canonical individual source-report corpus.
- `knowledge-packs/compiled-packs/` contains grouped upload packs.
- `knowledge-packs/omnibus/` contains the full canon as one bundle.

Do not create or expect `docs/reports/`. The reports live in `knowledge-packs/by-report/`.

---

## Recommended Default

Use the **compiled packs** unless you have a specific reason not to. They preserve the canon sequence while keeping upload count low.

| Pack Type | Files | Best Use | Use When |
|---|---:|---|---|
| Source reports | 12 | Precise retrieval, selective upload, citation, editing, source repair. | Your tool handles many files well, or you need report-level provenance. |
| Compiled packs | 4 | Default AI/RAG upload format. Balanced coverage with lower file count. | You want strong structure without a single giant file. |
| Omnibus | 1 | One-file import, local archive, full-corpus search, strong long-context systems. | Your tool prefers one large source or you want an archival copy. |

---

## Pack Selection by Workflow

| Workflow | Recommended Pack | Rationale |
|---|---|---|
| ChatGPT Project / custom assistant knowledge | Compiled packs | Four files usually fit upload constraints while keeping the sequence legible. |
| NotebookLM-style corpus work | Compiled packs or source reports | Use compiled packs for fewer files; source reports when source-level citation matters. |
| Vector database / RAG ingestion | Source reports | Smaller canonical units make retrieval, metadata filtering, and citation auditing cleaner. |
| Long-context manual analysis | Omnibus | One complete file reduces file handling friction. |
| Corpus editing or source repair | Source reports | Edit canonical source units, not compiled convenience bundles. |
| Local search or archive | Omnibus + manifest | One searchable file plus explicit mappings. |

---

## Source Reports

These are the canonical individual units of the corpus.

- [A. The Geometry of Strategic Conflict — An Ontology of Incentives, Interdependence, and Equilibrium.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/a-the-geometry-of-strategic-conflict.md)
- [B. Equilibrium and Information — Stability, Beliefs, and Strategic Knowledge Systems.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/b-equilibrium-and-information.md)
- [C. Strategic Representation and Formalization — Modeling Strategic Reality with Matrices, Trees, Information Sets, and Type Spaces.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/c-strategic-representation-and-formalization.md)
- [D. Sequential Strategy and Dynamic Commitment — Timing, Credibility, and Subgame Structure.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/d-sequential-strategy-and-dynamic-commitment.md)
- [E. Bargaining, Coalition Pressure, and Surplus Division — Strategic Settlement Under Conflict and Mutual Dependence.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/e-bargaining-coalition-pressure-and-surplus-division.md)
- [F. Repeated Interaction, Reputation, and the Shadow of the Future — Cooperation, Punishment, and Relational Stability.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/f-repeated-interaction-reputation-and-the-shadow-of-the-future.md)
- [G. Mechanism Design and Institutional Engineering — Designing Rules So Incentives Produce Desired Outcomes.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/g-mechanism-design-and-institutional-engineering.md)
- [H. Evolutionary and Population Game Dynamics — Strategy Without Deliberation.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/h-evolutionary-and-population-game-dynamics.md)
- [I. Networked Games, Externalities, and Systemic Inefficiency — Coordination Failure, Congestion, and the Price of Anarchy.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/i-networked-games-externalities-and-systemic-inefficiency.md)
- [J. Strategic Failure and Diagnostic Analysis — Hidden Incentives, Fragility, and System Reconstruction.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/j-strategic-failure-and-diagnostic-analysis.md)
- [K. System Reconstruction and Applied Strategic Method — Modeling Workflow, Validation, and Decision Support.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/k-system-reconstruction-and-applied-strategic-method.md)
- [L. Institutional Evolution and Strategic Ecology — Long-Run Adaptation, Succession, and Civilizational Stability.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/by-report/l-institutional-evolution-and-strategic-ecology.md)

---

## Compiled Packs

These are grouped convenience files for upload-constrained systems.

- [[KNOWLEDGE] - Game Theory - Vol. 1 A-C Foundations of Strategic Reality.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/compiled-packs/knowledge-game-theory-vol-1-a-c-foundations-of-strategic-reality.md) — foundations, equilibrium, information, and representation.
- [[KNOWLEDGE] - Game Theory - Vol. 2 D-G Major Operating Domains.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/compiled-packs/knowledge-game-theory-vol-2-d-g-major-operating-domains.md) — sequence, commitment, bargaining, repeated interaction, reputation, and mechanism design.
- [[KNOWLEDGE] - Game Theory - Vol. 3 H-J Constraint and Specialization Layers.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/compiled-packs/knowledge-game-theory-vol-3-h-j-constraint-and-specialization-layers.md) — evolutionary dynamics, networks, externalities, systemic inefficiency, and failure diagnosis.
- [[KNOWLEDGE] - Game Theory - Vol. 4 K-L Diagnostic and Execution Layers.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/compiled-packs/knowledge-game-theory-vol-4-k-l-diagnostic-and-execution-layers.md) — reconstruction, applied method, validation, decision support, and institutional evolution.

---

## Omnibus

- [[KNOWLEDGE] - Game Theory - Omnibus.md](https://github.com/Stunspot/stunspots-guide-to-game-theory/blob/main/knowledge-packs/omnibus/knowledge-game-theory-omnibus.md)

The omnibus is the whole canon in one file. Use it for archive, local search, and long-context systems that perform well with a single large source.

---

## Ingestion Notes

For RAG pipelines, attach metadata before chunking where possible:

```json
{
  "canon": "Stunspot's Guide to Game Theory",
  "version": "1.0",
  "pack_type": "source_report | compiled_pack | omnibus",
  "report_code": "A-L where applicable",
  "repository_path": "knowledge-packs/...",
  "license": "CC BY-NC-SA 4.0"
}
```

The report code is useful because the canon is sequential. A model answering from Report K should know that Reports A-J define the primitives it is using.
