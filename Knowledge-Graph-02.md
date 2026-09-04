# KNOWLEDGE GRAPH

Nodes are the Ontology. Edges are what actually connects them:

`DERIVED_FROM` — Evidence → Source
`SUPPORTS` — Evidence → Claim
`INTERPRETS` — Interpretation → Claim
`ANSWERS` — Hypothesis → Question
`TRIGGERS` — Hypothesis/Interpretation → Decision
`REJECTS` — Decision → [alternatives not taken]
`APPLIES` — Transformation → Interpretation
`TESTS` — Experiment → Transformation
`PRODUCES` — Result → Experiment
`BECOMES_CANON` — Result/Decision → Canon
`CONTRADICTS` — Claim/Decision ↔ Claim/Decision
`FORKS_FROM` — Fork → Dossier/Core
`CITES` — Fork/Contributor → Source/Result

**Seed graph — the one path that's actually populated right now:**

```
SRC-001 (Saint Peter's Basilica, cruciform plan)
   → EVD-001 (unbroken cruciform footprint, F1)
   → CLM-001 ("the plan can be borrowed whole", F3)
   → DEC-001 ("keep Peter's plan unaltered", D1)
       — REJECTS: modifying the cruciform footprint to fit the domes
   → TRF-001 (constraint-preservation: hold one source fixed while transforming the rest)
   → RES-001 (the cruciform plan carrying seven non-religious ziggurat domes)
   → BECOMES_CANON → Constitution, Article I

CONTRADICTS: RES-001 ↔ CLM-014 ("the seven domes are structurally plausible, buildable")
   — because RES-001's dome count was chosen for meaning, not derived from CLM-014's structural logic
   — this is C1 in the Dark Forest Contradiction Map
```

Everything else in MERIDIAN is this same shape, unpopulated. Filling Dossier I's actual Source, Evidence, and Claim registers is what turns the rest of this graph from a schema into a real graph.
