# Governance
**Governance** keeps our collaboration transparent, evidence-driven, and fair — for everyone. 🌍

## Decision principle
All contributions are welcome that improve:
- interoperability
- verifiability (testability, evidence)
- security-by-design
- clarity and reuse across domains

## Why we differentiate roles

Within Git environments we often use the term **maintainer**, but for our **Trust Union** it sounds like *caretaking* rather than *standard-setting*.  
We differentiate roles to make responsibilities explicit, protect the **neutral zone**, and avoid hidden power structures.

This separation ensures:
- **Clarity:** everyone knows who decides *what* and *why*.
- **Neutrality:** content decisions are not driven by platform control.
- **Quality:** editorial consistency is handled without “governance power”.
- **Operability:** security, CI, and permissions are managed professionally (DevOps/Operations).

## Roles(*1)

### Stewards
Guard within a mission and the neutral zone.  
They decide on acceptance/rejection of **normative changes** (standards, principles, patterns) and ensure proposals remain evidence-based and interoperable.

### Editors
Shape and improve texts without owning decisions.  
They structure, condense, and align language for consistency and readability — **without governance authority**.

### Platform Admins
Operate the collaboration platform.  
They manage org/repo settings, security controls, CI, permissions, and operational reliability (DevOps/Operations) — **without influencing content decisions**.

### Contributors
Drive the work forward.  
They propose issues, submit pull requests, review changes, and provide references, examples, and verification ideas.

## Role assignment & community influence

Roles are **not exclusive**: one person may hold multiple roles, and roles can be reassigned as the community evolves.  
At the same time, Trust Union is **community-driven**: the community may always use democratic mechanisms — discussion, review, and visible consensus in Issues/PRs — to influence decisions and challenge proposals. 🗳️🤝


## Conflict of interest
If you represent an **organization/vendor**, disclose it in the relevant issue/PR.

(*1) 
## Why differentiated roles support Security-by-Design: 3 compact User Stories that matter...

### TRUST-01 — Evidence-based proposal (Contributor)
**As a** Contributor, **I want** to propose a security requirement as an Issue/PR, **so that** security properties become explicit and verifiable.

**Acceptance Criteria (Given/When/Then)**
- **Given** I submit a proposal, **when** it is opened as an Issue or PR, **then** it includes a clear requirement statement, rationale, and a verification/evidence approach.
- **Given** acceptance criteria are needed, **when** I describe expected behavior, **then** it is expressed in testable terms (not opinions or intentions).
- **Given** the proposal references context, **when** sources exist, **then** links or examples are attached.

---

### TRUST-02 — Neutral, review-based decision (Steward)
**As a** Steward, **I want** to review and decide on normative changes, **so that** standards stay neutral, interoperable, and auditable.

**Acceptance Criteria (Given/When/Then)**
- **Given** a PR changes normative content, **when** it is reviewed, **then** the decision rationale is documented in the PR conversation.
- **Given** a change introduces vendor-first or national-first framing, **when** it is detected, **then** the PR is revised or rejected with an evidence-based explanation.
- **Given** a change is high-impact or uncertain, **when** a decision is made, **then** at least one additional reviewer is invited.

---

### TRUST-03 — Platform integrity & community influence (Platform Admin + Community)
**As a** Platform Admin and Community, **I want** secure collaboration controls and transparent influence, **so that** artifacts remain trustworthy and decisions stay challengeable.

**Acceptance Criteria (Given/When/Then)**
- **Given** a contribution is proposed, **when** it affects normative artifacts, **then** branch protection requires review by someone other than the author before merge.
- **Given** the community raises substantiated objections, **when** concerns are posted in Issues/PRs, **then** they are addressed with documented rationale before a final decision stands.
- **Given** new evidence emerges, **when** prior decisions are questioned, **then** the change can be reopened and re-evaluated through the same transparent process.

