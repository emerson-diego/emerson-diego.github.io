# Technical Contract

## Runtime

- Use the repository's pinned language and runtime versions.
- Prefer the standard library and already-approved dependencies.
- Record a dependency decision when a new package is necessary.

## Boundaries

- Keep transport, domain logic, persistence, and external adapters separate.
- Treat public API schemas and persisted data formats as compatibility
  boundaries.
- Do not write credentials, local environment files, or generated artifacts to
  version control.

## Testing

- Unit tests cover local rules and small contracts.
- Integration tests cover service boundaries, adapters, and failure paths.
- End-to-end tests cover the real capability path at release boundaries.
- Manual acceptance covers operator workflow, recovery, and observable behavior
  that assertions cannot fully express.
