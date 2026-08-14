# PRAXIS MANTIS — Changelog

All notable changes to this project are documented in this file.

This project follows a research-grade, versioned release model.
Backward compatibility is preserved unless explicitly stated.

---

## [v3.6] — Governance-Ready Planning Release

### Added
- Explainable policy ranking output
- Deterministic candidate scoring and ordering
- Bounded multi-step mitigation planning
- Explicit refusal and halt semantics
- Budget-first, fail-closed planning guarantees
- Human-auditable mitigation plan artifacts (`mantis_plan.json`)

### Verified
- Absolute ISC budget enforcement
- No state mutation under any execution mode
- Identical legality rules across HYBRID / ASAP / EFF modes
- Policy fallback behavior under constrained budgets
- Deterministic output under identical inputs

### Intentionally Disabled
- Chronos audit commit (disabled by default)
- Autonomous execution
- Recursive or self-authorizing behavior

### Notes
This release formalizes PRAXIS MANTIS as a **governed policy planning engine**, not an actor.

MANTIS plans only.
Execution authority remains external.
