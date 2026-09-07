# Current Claude Code Features

This file tracks implementation-sensitive Claude Code behavior referenced by the book. Durable production principles remain in the manuscript; fast-moving flags, modes, preview features, UI details, model names, telemetry fields, and availability belong here.

**Last verified:** September 2026

## Track these feature families

- permission modes and rule syntax
- sandboxing and auto mode
- Skills
- Hooks and event semantics
- MCP scopes/transports/security
- subagents
- worktrees
- agent teams (experimental)
- plugins and LSP/code intelligence
- checkpointing
- GitHub Actions
- headless `claude -p`
- Agent SDK
- OpenTelemetry and tracing
- cost/context controls
- review tooling

## Feature record template

```markdown
# Feature

Status: Stable / Current / Preview / Experimental / Deprecated
Verified: YYYY-MM
Official docs: <link>
Book chapters: <refs>

## Current behavior

## Volatile details

## Migration notes
```

## Important book principle

A changed command or feature name should not invalidate the architecture. Preserve the control objective: context, authority, isolation, verification, security, observability, and recovery.
