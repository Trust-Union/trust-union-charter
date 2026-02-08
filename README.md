# Trust Union — Charter & Goals

## Purpose
Trust Union provides a neutral, EU-aligned collaboration space to define **auditable requirements** and **security-by-design** principles for **digital public infrastructures**, especially in regulated environments funded with public money.

*Vision and trust statement*:

Unite engaged people to create verifiable digital artifacts that maximize sovereignty and security — a trust union.

This idea follows the 

- Kerkhoff’s principle → transparency, traceability, and verifiability by design

- Git as the underlying infrastructure → proven, revision-safe versioning and traceability

- Open-source commitment → global interoperability and freedom from vendor lock-in


Every piece of software or hardware starts with requirements:
**Requirements → Acceptance Criteria → Automation → Verifiable Security Properties**
this results in:
**Security properties are only actionable when they are explicit, testable, and traceable.**

## Why this exists
**European digital infrastructures** are built in complex ecosystems (wallets, sandboxes, platforms, regulated domains).  
To scale cooperation, we need **standards** **shared, testable and evidence-based standards**


We structure the work across three connected fields:

### Requirements Engineering & IT Security by Design (cross-domain, EU-level)
- Define reusable requirement patterns for regulated environments.
- Translate security goals into **testable acceptance criteria**.
- Enable automation: checks, validators, compliance evidence.


## Scope (initial)
- A sector-agnostic catalog of security properties (e.g., integrity, authenticity, isolation, key protection, update assurance)
- A structure to express requirements **per component / per trust-boundary**
- Issue & review workflows to refine requirements collaboratively
- Example packs that demonstrate how to document component-wise security requirements (as examples, not as the scope)


## Principles
- Evidence-based: every requirement is paired with verification ideas.
- Composable: small patterns that can be reused across domains.
- Neutral: sector-specific mappings are optional and derived, never assumed.


## How we work
- Proposals start as Issues that are based on fact-based pain points in the digital wild.
- Merges happen through PRs with clear acceptance criteria.
- Every requirement pattern includes: goal, rationale, acceptance criteria, verification approach.


## Neutral Zone Principle
This repository is a **neutral zone**:
- No vendor-first thinking.
- No national-first framing.
- No hidden strategic agenda.
- Decisions must be explainable via requirements, evidence, and interoperability.

We explicitly eliminate particular interests by design:  
**If it cannot be validated, it is not a standard.**

## Working Method
- Everything is tracked as issues, discussions, and pull requests.
- Proposals must include: goal, rationale, acceptance criteria, and verification approach.
- Prefer minimal, composable artifacts over large documents.


## Repo Structure of Trust Union — Charter
```text
/charter/               # Trust Union: Neutral Zone, Principles, Governance (summary)
/patterns/              # Requirement Patterns (agnostic)
/patterns/acceptance/   # Acceptance-Criteria Patterns
/patterns/evidence/     # Verification/Evidence Patterns
/templates/             # Issue/PR Templates
```

## Next Steps
1. Define initial terminology & glossary.
2. Establish contribution rules and decision process.
3. Create the first set of requirement templates and acceptance-criteria patterns.
