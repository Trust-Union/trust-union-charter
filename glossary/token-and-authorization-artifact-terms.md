# Token and Authorization Artifact Terms

Status: Draft  
Scope: Sector-agnostic  
Note: This glossary is explanatory, not normative.

## Purpose

This glossary stabilizes the terminology around tokens, authorization artifacts, token binding, and token representation.

It distinguishes clearly between:
- function,
- binding, and
- format.

These dimensions should not be conflated.

## Core distinction

A token can be classified along different dimensions:

- **Function**: what the token is used for
- **Binding**: what must be demonstrated when using it
- **Format**: how it is represented technically

These properties are orthogonal.
The same functional token may appear in different technical formats and may be used with different binding properties.

## Terms

### Token

A context-dependent digital artifact that represents a value, object, claim, entitlement, or authorization context.

### Security token

A generic term for a token used in a security-relevant context, such as authentication, authorization, or cryptographic proof.

### Authorization artifact

A digital artifact that conveys rights, permissions, roles, scopes, entitlements, or authorization context relevant to a protected action.

### Authorization token

A token that represents authorization-relevant information, such as permissions, scopes, roles, or delegated rights.

### Access token

A token presented by a client when requesting access to a protected resource or service.

An access token is an authorization artifact.
It expresses or references the authorization context under which access is requested.

### Authentication artifact

An artifact used to prove an identity, the presence of an additional factor, or possession of a credential.

Examples include:
- one-time passwords,
- smartcards,
- passkeys,
- FIDO security keys.

### Bearer token

A token that can be used by any party in possession of it, without proving possession of an additional cryptographic key bound to the token.

### Sender-constrained token

A token that is cryptographically bound to its presenter or sender.

Possession of the token value alone is not sufficient.
The presenter must also demonstrate possession of the associated cryptographic key or equivalent proof material.

### Opaque token

A token whose content is not self-describing to the recipient.

Its meaning, state, or authorization context typically requires server-side lookup, metadata retrieval, or introspection.

### JSON Web Token (JWT)

A compact token format for representing claims as a JSON object.

A JWT is a token format, not a trust decision by itself.
Its contents become trustworthy only after the receiving system applies the required validation steps for integrity, origin, and other relevant constraints.

### Binding

The usage property that defines what must be demonstrated when presenting a token.

Examples include:
- bearer use,
- sender-constrained use.

### Format

The technical representation of a token as a digital artifact.

Examples include:
- opaque token values,
- JSON Web Tokens.

### Token introspection

A protocol-based lookup of metadata about a token, typically performed by a protected resource against an authorization service or equivalent authority.

Token introspection is especially relevant when token meaning cannot be determined locally and must be retrieved from an authoritative source.

## Notes

- Not every token is an access token.
- Not every access token is a JWT.
- A JWT is a format, not a synonym for access token.
- A token format does not, by itself, determine whether the token is bearer or sender-constrained.
- Authentication artifacts and authorization artifacts should be kept distinct unless a project deliberately defines a combined model.
