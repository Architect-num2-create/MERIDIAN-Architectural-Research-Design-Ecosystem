# MERIDIAN — RESEARCH LEDGER

**Project:** MERIDIAN  
**System:** Transformation Architecture Thesis  
**Document:** Research Ledger  
**Version:** 0.1.0  
**Status:** Active  
**Author:** [Your Name]  
**Institution:** [University / Studio]  
**Created:** [YYYY-MM-DD]  
**Last Updated:** [YYYY-MM-DD]

---

# 00 — PURPOSE

The MERIDIAN Research Ledger is the project's traceability system.

It records the development of knowledge from source material to architectural
decision.

The Ledger does not function as a bibliography.

It functions as a structured memory of:

- what was found
- where it was found
- what the evidence actually supports
- what was inferred
- what was questioned
- what was hypothesized
- what was tested
- what was rejected
- what was transformed
- what entered the architecture
- and what remains unresolved

The central principle is:

> No important architectural decision should become
> epistemically orphaned.

Whenever possible, the path from evidence to architecture should remain
recoverable.

---

# 01 — THE TRACEABILITY CHAIN

The primary MERIDIAN knowledge chain is:

SOURCE
↓
EVIDENCE
↓
CLAIM
↓
INTERPRETATION
↓
QUESTION
↓
HYPOTHESIS
↓
DECISION
↓
TRANSFORMATION
↓
EXPERIMENT
↓
ARCHITECTURAL RESULT

This chain is not necessarily linear.

One source may produce multiple claims.

One claim may produce multiple hypotheses.

One hypothesis may produce multiple experiments.

Multiple historical sources may converge into one transformation.

One architectural result may therefore have multiple genealogies.

---

# 02 — ID SYSTEM

Every significant research object receives a unique identifier.

## Source

`SRC-###`

Example:

`SRC-001`

---

## Evidence

`EVD-###`

Example:

`EVD-014`

---

## Claim

`CLM-###`

Example:

`CLM-008`

---

## Interpretation

`INT-###`

Example:

`INT-005`

---

## Question

`QST-###`

Example:

`QST-021`

---

## Hypothesis

`HYP-###`

Example:

`HYP-004`

---

## Decision

`DEC-###`

Example:

`DEC-013`

---

## Transformation

`TRF-###`

Example:

`TRF-009`

---

## Experiment

`EXP-###`

Example:

`EXP-017`

---

## Architectural Result

`RES-###`

Example:

`RES-006`

---

## Rejected Proposition

`REJ-###`

Example:

`REJ-011`

---

## Open Problem

`OPR-###`

Example:

`OPR-003`

---

# 03 — EPISTEMIC STATUS

Every knowledge object must be distinguished by epistemic status.

### F1 — Established Fact

Directly supported by reliable primary or authoritative evidence.

### F2 — Scholarly Consensus

Supported by substantial relevant scholarship.

### F3 — Plausible Scholarly Interpretation

A defensible interpretation that remains open to disagreement.

### I1 — Authorial Interpretation

An interpretation developed by the MERIDIAN project.

### H1 — Working Hypothesis

A proposition currently being investigated or tested.

### X1 — Experimental Proposition

A proposition introduced specifically for design experimentation.

### U1 — Unknown

Insufficient evidence currently exists.

### R1 — Rejected

A proposition, interpretation, experiment, or direction rejected by the project.

### D1 — Design Decision

A deliberate architectural decision made within the project.

---

# 04 — SOURCE REGISTER

The Source Register provides the master index of all significant sources.

| ID | Source | Type | Date | Domain | Reliability | Used For | Status |
|---|---|---|---|---|---|---|---|
| SRC-001 | [Source] | Primary / Scholarly / Institutional / Other | [Date] | [Domain] | [High/Med/Low] | [Purpose] | Active |

---

# 05 — EVIDENCE REGISTER

Evidence records what a source actually provides.

Evidence must be separated from interpretation.

| ID | Source ID | Evidence | Location | Type | Status | Notes |
|---|---|---|---|---|---|---|
| EVD-001 | SRC-001 | [Observed evidence] | [Page/Figure/etc.] | Visual/Textual/Measured | F1 | [Notes] |

Evidence should describe what is present before explaining what it means.

---

# 06 — CLAIM REGISTER

Claims are statements derived from evidence.

| ID | Evidence | Claim | Epistemic Status | Confidence | Domain | Notes |
|---|---|---|---|---|---|---|
| CLM-001 | EVD-001 | [Claim] | F2 | High | Spatial | [Notes] |

A claim must not silently become a fact merely because it is useful to the
design.

---

# 07 — INTERPRETATION REGISTER

Interpretations describe what MERIDIAN believes a piece of evidence or
historical logic may mean architecturally.

| ID | Claim | Interpretation | Status | Architectural Potential |
|---|---|---|---|---|
| INT-001 | CLM-001 | [Interpretation] | I1 | [Potential] |

---

# 08 — QUESTION REGISTER

Questions are treated as active research objects.

| ID | Origin | Question | Domain | Importance | Status |
|---|---|---|---|---|---|
| QST-001 | INT-001 | [Question] | Theory | High | Open |

Questions should not be removed merely because they remain unanswered.

An unresolved question may become a future research direction.

---

# 09 — HYPOTHESIS REGISTER

Hypotheses convert questions into testable propositions.

| ID | Question | Hypothesis | Prediction | Test | Status |
|---|---|---|---|---|---|
| HYP-001 | QST-001 | [Hypothesis] | [Prediction] | [Test] | Active |

---

# 10 — DECISION REGISTER

Design decisions must be recorded as decisions rather than presented
retrospectively as inevitable outcomes.

| ID | Trigger | Decision | Alternatives | Reason | Evidence | Status |
|---|---|---|---|---|---|---|
| DEC-001 | HYP-001 | [Decision] | [Alternatives] | [Reason] | [IDs] | Active |

---

# 11 — TRANSFORMATION REGISTER

This is one of the central registers of MERIDIAN.

A transformation records how extracted historical logic becomes something new.

| ID | Source Logic | Input | Operation | Constraint | Output | Related IDs |
|---|---|---|---|---|---|---|
| TRF-001 | [Logic] | [Input] | [Operation] | [Constraint] | [Output] | [IDs] |

Possible transformation operations include:

- abstraction
- mutation
- inversion
- scaling
- compression
- expansion
- fragmentation
- aggregation
- rotation
- repetition
- subtraction
- substitution
- hybridization
- spatialization
- structural reinterpretation
- environmental reinterpretation
- material reinterpretation
- proportional transformation
- geometric transformation

The operation itself must be documented.

---

# 12 — EXPERIMENT REGISTER

Experiments test whether a transformation actually produces a meaningful
architectural condition.

| ID | Transformation | Experiment | Variable | Expected Result | Actual Result | Status |
|---|---|---|---|---|---|---|
| EXP-001 | TRF-001 | [Experiment] | [Variable] | [Expected] | [Observed] | Active |

---

# 13 — RESULT REGISTER

Architectural results are recorded after experimentation.

| ID | Experiment | Result | Architectural Effect | Evidence | Status |
|---|---|---|---|---|---|
| RES-001 | EXP-001 | [Result] | [Effect] | [IDs] | Accepted |

---

# 14 — REJECTION REGISTER

MERIDIAN preserves failure.

| ID | Origin | Rejected Proposition | Why Rejected | What Was Learned | Possible Future Use |
|---|---|---|---|---|---|
| REJ-001 | [ID] | [Proposition] | [Reason] | [Learning] | [Potential] |

A rejection should not be interpreted automatically as failure.

It may define the boundary conditions of the design system.

---

# 15 — OPEN PROBLEM REGISTER

| ID | Related IDs | Problem | Why It Matters | Current State | Next Investigation |
|---|---|---|---|---|---|
| OPR-001 | [IDs] | [Problem] | [Importance] | Open | [Next step] |

---

# 16 — DESIGN GENEALOGY

Important architectural elements should eventually have a genealogy.

Example:

```text
Historical Source
      ↓
SRC-###
      ↓
EVD-###
      ↓
CLM-###
      ↓
INT-###
      ↓
QST-###
      ↓
HYP-###
      ↓
DEC-###
      ↓
TRF-###
      ↓
EXP-###
      ↓
RES-###
      ↓
ARCHITECTURAL ELEMENT
