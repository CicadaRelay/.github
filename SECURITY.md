# Security Policy

## Supported scope

CicadaRelay repositories often touch:

- model routing
- deployment tooling
- network fabrics
- hardening and pre-exposure controls
- local and distributed operator environments

Security issues in these areas should be treated seriously.

## Reporting a vulnerability

Please do not open a public issue for a suspected vulnerability that could expose:

- credentials
- deployment secrets
- remote access paths
- routing control surfaces
- host hardening gaps

Instead, report privately to the maintainers through GitHub security reporting when available, or through a trusted direct contact channel.

## Disclosure expectations

- provide steps to reproduce when possible
- include affected repositories and paths
- include impact and attack preconditions
- avoid publishing exploit details before maintainers have time to assess and patch

## Hardening principle

The default expectation across CicadaRelay projects is:

- explicit access boundaries
- observable routing
- least-exposed defaults
- no trust in a perfect environment
