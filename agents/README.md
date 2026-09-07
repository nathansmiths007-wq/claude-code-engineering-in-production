# Specialist Agents

These role definitions implement the book's separation of implementation, verification, and security judgment.

## Explorer
Read-only repository mapping. Returns confirmed facts, relevant paths/symbols, contracts/tests, security boundaries, inference, and unknowns.

## Planner
Converts an approved specification plus repository evidence into a bounded implementation plan, dependency graph, shared contracts, migration/security notes, and verification map.

## Developer
Implements the approved scope in an isolated worktree. Must not silently redefine requirements, weaken oracle tests, expand scope, or modify the harness to make work easier.

## Tester
Independently verifies acceptance criteria. The Tester owns the acceptance verdict, not the implementation agent.

## Reviewer
Reviews the integrated diff for correctness, scope, architecture, regression risk, and migration/recovery concerns.

## Security Reviewer
Challenges authorization, tenant isolation, secrets, untrusted content, plugins/MCP/Hooks, external writes, logging, and recovery.

## Structured handoff

Every editing workstream should return:

```text
Workstream
Base SHA
Contract version
Owned paths
Files changed
Requirements addressed
Tests run
Result
Blockers
Remaining uncertainty
Commit(s)
```

The detailed YAML/frontmatter examples in the book should be checked against `CURRENT_FEATURES.md` and current Claude Code documentation before use.
