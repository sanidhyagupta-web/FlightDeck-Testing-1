# Architecture Overview — flight-deck-testing-1

## System Topology

*None found.* This repository currently contains no application code. A full-tree scan found
only:
- `README.md` — a one-line title, no other content
- `scripts/onboard.sh` — onboarding/harness tooling, not part of the shipped system
- `.claude/` — the coding-agent harness (rules, agents, skills) this scaffold run itself added

There are no services, modules, packages, or apps — the target-enumeration scan (`services/`,
`modules/`, `packages/`, `apps/`, `pages/`, `features/`, `views/`, `routes/`, at any depth) found
nothing, and a full repo listing confirms no source directory of any kind exists.

## Tech Stack Per Layer

*None found.* No `package.json`, build file (`pom.xml`, `build.gradle`, `Cargo.toml`,
`pyproject.toml`, etc.), or CI configuration exists anywhere in the repository, so no language,
framework, or build tool can be determined.

## Cross-Cutting Architectural Decisions

*None found.* There is no code to have made a decision about yet.

## Coupling Graph

*None found.* No features exist to have dependency edges between (see `Features/index.md`).

---

*Open question: is this repository intentionally a pre-code scaffold (e.g. a fresh project
about to receive its first commit), or is application code expected to live in a location this
scan's directory-name heuristics didn't match? Re-run this skill in refresh mode once real
source code is added.*
