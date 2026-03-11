# CicadaRelay

### Deployable systems for OpenClaw, CLAW Mesh, routing, and hardening.

CicadaRelay is the infrastructure layer of the broader CLAW ecosystem.

This organization is where the operational pieces live:

- distributed control and node fabrics
- model routing and provider control layers
- deployment hardening and pre-exposure checks
- skill tooling and workflow infrastructure

The goal is not to build another AI demo stack.
The goal is to build systems that stay useful once AI work becomes operational, distributed, and persistent.

## Project Family

### Entry Layer

- [`CICADA`](https://github.com/2233admin/CICADA)
  Launcher product for getting users into the ecosystem quickly.

### Mesh and Distributed Execution

- [`claw-grid`](https://github.com/CicadaRelay/claw-grid)
  Implementation repository for the public-facing **CLAW Mesh** platform.
  This is the distributed control, governance, memory, and execution fabric.

### Routing and API Control

- [`claw-api-hub`](https://github.com/CicadaRelay/claw-api-hub)
  Unified API control hub for multi-provider routing, management, and cost discipline.

- [`clawapi-manager`](https://github.com/CicadaRelay/clawapi-manager)
  Provider control layer for OpenClaw with centralized API routing and runtime management.

- [`free-llm-hub`](https://github.com/CicadaRelay/free-llm-hub)
  Simple multi-gateway access layer for free and low-friction model access.

### Hardening and Integrity

- [`openclaw-hardener`](https://github.com/CicadaRelay/openclaw-hardener)
  Self-check and hardening tools for OpenClaw deployments before public exposure.

### Skills and Workflow Tooling

- [`clawhub-skill-tools`](https://github.com/CicadaRelay/clawhub-skill-tools)
  Tooling for building, organizing, and evolving deployable OpenClaw skills.

## Naming Strategy

The naming layers are intentional:

- `CLAW OS` = umbrella vision
- `CLAW Mesh` = public-facing distributed platform name
- `claw-grid` = implementation repository for that platform
- `Cicada` = launcher product
- `OpenClaw` = runtime and user environment

This org keeps repository names stable while allowing public product language to stay clear.

## Focus Areas

### Control

Control planes, schedulers, routing hubs, and operator-facing infrastructure.

### Mesh

Distributed node fabrics, worker coordination, and execution layers that can scale beyond a single machine.

### Access

Gateway and provider layers that make model access observable, replaceable, and operationally manageable.

### Hardening

Integrity checks, exposure controls, and deployment-safe defaults.

### Tooling

Skill systems, workflow kits, and supporting infrastructure for repeatable operator loops.

## Operating Principle

If a system only works inside a staged demo, it is not finished.

Everything here is meant to survive contact with real usage.
