# Policy Enforcement, Observability, and Detection Terms

Status: Draft  
Scope: Sector-agnostic  
Note: This glossary is explanatory, not normative.

## Purpose

This glossary stabilizes key terms used by **policy enforcement**, **monitoring**, and **detection patterns**.
It keeps requirement patterns technology-agnostic while making the underlying concepts explicit and reviewable.

## Terms

### Client registration

The process of assigning a persistent, unique, and reviewable identity to a client that interacts with a protected interface.

Client registration exists to make clients distinguishable for policy decisions, monitoring, accountability, and trust-boundary handling.

### Policy

A machine-readable rule or rule set that determines whether a requested action is allowed, denied, or subject to conditions.

### Policy enforcement function

The gatekeeping function that applies policy before a protected action is executed.

### Policy information function

The function that provides decision-relevant attributes, signals, and contextual data used during policy evaluation.

### Policy administration function

The function responsible for creating, managing, distributing, updating, and publishing policy rules.

### Observation data

Data derived from policy decisions and their runtime context.

Typical examples include:
- decision result,
- timestamp,
- client or caller identity,
- resource or interface,
- contextual attributes,
- anomaly indicators,
- change-related metadata.

### Operational parameters

Measurable runtime characteristics relevant to service behavior or policy enforcement.

Examples may include throughput, latency, error rates, saturation indicators, policy hit counts, or rejection rates.

### Telemetry data

Machine-generated runtime data used to understand system behavior and the effects of policy decisions or policy changes.

Telemetry may include logs, metrics, events, traces, and derived runtime signals.

### Monitoring

The continuous or repeated evaluation of operational parameters and telemetry data in order to assess whether policies are enforced as intended and whether effective policy changes have relevant effects.

### Detection logic

A formalized rule or rule set used to identify suspicious, malicious, or policy-relevant behavior from runtime data.

### SIEM

Security Information and Event Management.

A SIEM is an analysis platform or product category that collects, correlates, and analyzes data from multiple sources in order to detect, investigate, and support response to security-relevant events.

A SIEM is an implementation option, not a requirement of Trust Union patterns.

### Sigma rule

A portable, shareable detection rule written in an open format and intended to describe suspicious or malicious behavior in a tool-neutral way.

A Sigma rule is not the analysis platform itself.
It is a portable expression of detection logic that may be translated into product-specific query or rule formats.

### Product-specific detection rule

A rule expressed in the syntax, query language, or rule model of a specific analysis product.

It represents a concrete implementation of detection logic in a given execution environment.

### Shared threat intelligence

Shared threat intelligence means exchanging security-relevant knowledge between organizations or systems.

Examples include:
- suspicious IP addresses,
- domains,
- file hashes,
- attack patterns,
- observed tactics,
- detection logic.

### Shared signals

Shared signals are machine-usable observations or indicators exchanged to improve detection, decision-making, or coordinated defense across organizational or technical boundaries.

## Notes

- Trust Union patterns define required properties and outcomes, not mandatory products.
- SIEM platforms and Sigma rules are useful examples for observability and detection ecosystems, but they are not normative dependencies.
- A project may use equivalent concepts or tools as long as the required properties remain explicit, testable, and traceable.
