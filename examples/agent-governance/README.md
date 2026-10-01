# Sanitized Agent Governance Example

This directory is a small teaching fixture for the workflow described in
`beyond-vibe-coding.html`. It shows how a project constitution and `AGENTS.md`
can give an agent durable context without exposing production code,
credentials, infrastructure details, or domain-sensitive rules.

The files are intentionally generic. They are not universal OpenSpec rules and
they do not force an agent to follow anything. Adapt them to the host tool,
repository, CI system, and risk profile of the project.

Suggested reading order:

1. `docs/constitution/mission.md`
2. `docs/constitution/tech-stack.md`
3. `docs/constitution/roadmap.md`
4. `AGENTS.md`

OpenSpec remains change-scoped: use the repository's chosen schema and CI
validation for material changes, while keeping this constitution stable and
small.
