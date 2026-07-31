# Closed-Baseline Capture and Integrity Tabletop Run

Status: active

CapacityOS Run: `purity-protocol#RUN-20260731-021056-purity-progress`

Parent Run: `RUN-20260731-repository-work-cycle-cai-hourly`

Date: 2026-07-31

Class: runtime

## Formal Phase Packet

- repo: `purity-protocol`
- workflow: `system-runtime#repo-progress-run`
- mode: `system-canon#execute`
- lane: `1`
- starting revision: `2a360e7055b4`
- write boundary: `CAPTURE-AND-INTEGRITY-CLOSED-BASELINE-TABLETOP.md`,
  `FIRST-ELIGIBILITY-GATE-EVIDENCE-SPECIFICATION.md`,
  `PHASE-0-GRADUATION-PACKET.md`, and this receipt
- method refs: [`purity-protocol#RESEARCH.md`,
  `purity-protocol#FIRST-ELIGIBILITY-GATE-EVIDENCE-SPECIFICATION.md`]

## Target

Purity Protocol Lane 1 — produce the evidence-supported Phase 0 graduation
packet.

## Objective

Execute a finite, closed-baseline synthetic tabletop that tests whether current
repository controls visibly stop representative capture and integrity failure
paths before any future eligibility role, participant, incentive, or live
mechanism exists. This advances the required capture-and-integrity evidence
bundle while preserving every unresolved rights, consent, capacity, and
activation question.

## Context Reads

- `AGENTS.md`, `CONSTITUTION.md`, `DECISIONS.md`, `GOVERNANCE.md`, `STATUS.md`,
  `ROADMAP.md`, `LANES.yaml`, `LANE-STATE.yaml`, and `RESEARCH.md`
- `FIRST-ELIGIBILITY-GATE-EVIDENCE-SPECIFICATION.md`
- `PHASE-0-GRADUATION-PACKET.md`
- recent complete runs through `RUN-20260727-071103-purity-progress.md`
- System Operations Purity Protocol steward service
- `repository-work-cycle`, `repo-progress-run`, and required safety flows

## Lane Selection and Safety

- Lane 1 is active, automation-eligible, and permits bounded synthetic
  prototypes and adversarial analysis that feed the Phase 0 packet. Its
  manifest digest is `sha256:1fd491042c0491b29b57af3c0b1ba168174db8d2c8dfd0334de21491f8b5c749`;
  definition/control revisions are `3` / `2`.
- The owner tree was clean and even with `origin/main` at `2a360e7055b4` when
  the session guard opened. The writer lock was absent. No recent run within
  the one-hour collision window is open or overlaps this new tabletop path.
- Run mode is scheduled/non-interactive. The working-tree classification is
  clean. The declared writable footprint is exactly the four paths in the
  formal packet.
- Effective authority permits founder-only, repository-local synthetic
  research and evidence reconciliation. It forbids an eligibility role, gate,
  authority transfer, governance or claim-status change, legal conclusion,
  participant or contributor activity, incentive, deployment, private data,
  and every non-GitHub external action.
- No emergency revocation is present. Ordinary control policy is
  `continue_current`; an emergency revocation, owner/manifest mismatch,
  writer lock, source-boundary breach, footprint expansion, or failed
  validation stops the run.

## Joe-Review Points

Joe alone may define or approve any role, threshold, gate, rights posture,
legal review, satisfaction finding, activation, or Phase 0 disposition. A
synthetic finding cannot establish real-world capture resistance or capacity.

## Plan

1. Define a small fictional closed-baseline record set and predeclared failure
   criteria for representative integrity threats.
2. Execute the cases only against current repository authority and preserve
   the resulting stops, residual risks, and limits.
3. Reconcile the evidence specification and graduation packet without
   upgrading any claim or implying a future role is safe.
4. Revalidate Lane selection, authority, writer lock, and exact footprint;
   validate; append the receipt; then commit and push the coherent owner work.

## Execution Notes

Plan created after the formal packet, local authority, recent-run collision,
writer-lock, and session-sync checks. No owner effect has occurred yet.

The first concrete attempt constructed eleven fictional pressure cases against
the closed baseline. Each case required either an explicit denial of inferred
authority or a visible stop on reliance. The resulting tabletop creates no
participant, role, threshold, mechanism, source claim, or external state.
It records the residual uncertainty instead of converting a synthetic control
into a claim of capture resistance.

The exact matching evidence references in the gate specification and
graduation packet now distinguish this negative control from the still-missing
candidate-specific threat model, real-world evidence, and rights boundary.

## Next-Work Handoff

- current work: closed-baseline capture and integrity tabletop
- current disposition: `ENDPOINT_POSITIVE`
- durable priority owner: Purity Protocol Lane 1 under Joe governance
- recommendation status: advisory

| rank | eligible lane or work item | why now | dependencies / gates |
|---:|---|---|---|
| 1 | Define whether to seek an exact rights/provenance review boundary. | The capture control confirms that a future role cannot rely on implied authority; the existing source comparison identifies rights and provenance as the earliest hard dependency. | Joe must choose the review question and appropriate review route; no legal conclusion or role design is authorized. |

- recommended next: Joe decision on whether to request appropriate legal review
  for a specified documentation/specification and future-contribution boundary.
- switch signal: this tabletop adds synthetic denial evidence but does not
  remove the rights/provenance, consent, capacity, or candidate-role gates.
- strongest alternative: a candidate-specific threat model; lower because it
  requires the still-unselected role and rights boundary.
- overturning evidence: a Joe-directed review scope or a ratified owner change
  that defines a lawful candidate boundary.
- steward reconciliation needed: no; this is a repository-local evidence
  addition and changes no Lane semantic state.

## Validation

- `python3 scripts/validate_repository.py`: passed.
- `git diff --check`: passed.
- Exact content review: the tabletop uses only fictional constructions and
  current repository authority; every case preserves a residual-risk limit.
- Effect-boundary revalidation: owner identity, starting branch revision,
  Lane manifest digest and active control, closed eligibility state, absent
  writer lock, and exact four-path footprint matched. No emergency revocation
  was found.

## Receipt

Outcome: progressed

- Material effect: a bounded synthetic evidence surface now tests eleven
  representative capture and integrity pressure paths against the current
  closed baseline, with explicit no-go conditions and residual risks.
- Actual footprint:
  - `CAPTURE-AND-INTEGRITY-CLOSED-BASELINE-TABLETOP.md`
  - `FIRST-ELIGIBILITY-GATE-EVIDENCE-SPECIFICATION.md`
  - `PHASE-0-GRADUATION-PACKET.md`
  - `runs/RUN-20260731-021056-purity-progress.md`
- Owner/Lane: `purity-protocol` / `1`.
- Formal workflow/mode: `system-runtime#repo-progress-run` /
  `system-canon#execute`.
- Required-flow attestation: `standard-run-safety-check`, `select-lane`,
  `create-run-plan`, `revalidate-lane-selection`, and `append-run-receipt`
  completed with no exception.
- Conditional flows invoked: `classify-artifact-disposition`,
  `rerank-next-work`.
- Conditional flows not invoked: `refresh-lane-state`,
  `evaluate-run-with-rubric`; no semantic Lane-state change or requested
  rubric existed.
- Method refs / effect: [`purity-protocol#RESEARCH.md`,
  `purity-protocol#FIRST-ELIGIBILITY-GATE-EVIDENCE-SPECIFICATION.md`] /
  applied the repository research discipline through predeclared fictional
  cases, evidence limits, falsifiers, residual risks, and disposition.
- Manifest digest: `sha256:1fd491042c0491b29b57af3c0b1ba168174db8d2c8dfd0334de21491f8b5c749`;
  Lane definition/control revision: `3` / `2`.
- Writer-lock evidence: absent at selection and effect-boundary revalidation.
- Recent-run collision: no live Purity writer or overlapping writable surface
  existed; the prior source-boundary comparison was complete and this run used
  a distinct synthetic evidence path.
- Artifact disposition: all four paths are deliberate repository-owned
  versioned knowledge; no third-party material was copied into the repository.
- External actions: routine GitHub versioning only; no non-GitHub external
  action occurred.
- Attention route / awareness pointer: Joe decision on whether to request an
  appropriate legal review for an exact future material/contribution boundary.
