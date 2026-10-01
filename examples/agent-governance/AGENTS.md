# Repository Agent Guidance

## Read Before Material Changes

Consult the three constitution files before proposing or implementing a
material change:

- `docs/constitution/mission.md`
- `docs/constitution/tech-stack.md`
- `docs/constitution/roadmap.md`

If the change affects a public contract, persistence, deployment, or a
security-sensitive boundary, summarize the impact and ask for explicit human
confirmation before applying it.

## Scope

- Write only inside the repository root.
- Do not introduce dependencies without explaining the need and checking the
  approved stack.
- Keep the change small enough to validate in a coherent loop.
- Update the relevant specification or acceptance criteria when behavior
  changes.

## Validation

Run the narrowest useful checks first, then the broader suite at the capability
boundary. Include manual acceptance when behavior, recovery, or operator
experience cannot be captured by automated assertions.

## Important Boundary

These are repository conventions, not universal properties of `AGENTS.md`,
OpenSpec, or any particular agent. The host tool decides whether it discovers
this file, how it prioritizes the instructions, and whether CI enforces them.
