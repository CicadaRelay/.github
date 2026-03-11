# Contributing to CicadaRelay

Thank you for contributing to CicadaRelay.

This organization is for deployable systems, not speculative demos. Contributions should improve operability, clarity, reliability, or maintainability.

## What belongs here

- routing and provider control layers
- distributed execution and mesh infrastructure
- deployment hardening and integrity tooling
- workflow systems and reusable operator tooling
- documentation that makes real deployment easier

## What does not belong here

- vague concept work with no execution path
- UI-only changes with no operational value
- large naming churn without clear migration value
- breaking protocol changes without an explicit compatibility plan

## Naming and architecture

Follow the naming strategy defined by the project family:

- `CLAW OS` = umbrella vision
- `CLAW Mesh` = public-facing distributed platform name
- `claw-grid` = implementation repository for that platform
- `Cicada` = launcher product
- `OpenClaw` = runtime and user environment

Do not rename implementation paths just to match public branding.

## Pull request expectations

Each pull request should clearly state:

- what changed
- why the change is needed
- whether behavior changed
- how the change was validated
- what risks remain

Prefer small, reviewable pull requests over broad rewrites.

## Documentation expectations

If a change affects operators, deployment, naming, or public-facing behavior, update the relevant docs in the same pull request.

## Security and exposure

Do not expose secrets, private keys, tokens, or production credentials.

For security-sensitive issues, follow `SECURITY.md`.
