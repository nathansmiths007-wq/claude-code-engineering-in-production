# Troubleshooting Reference

Use recovery-oriented diagnosis rather than repeatedly prompting the agent to try something else.

## Context pollution

Preserve specification, decisions, Git state and tests; use fresh context when old assumptions dominate.

## Hallucinated API

Verify installed version, official docs, type information/source, and runtime help before patching around a nonexistent interface.

## Test manipulation

Inspect every changed oracle. Restore weakened expectations, reproduce the failure, fix production code, and rerun affected regression.

## Agent collision

Freeze integration, identify the authoritative contract, choose one writer, rebase/discard stale dependent work, integrate in dependency order, and rerun combined verification.

## Permission problems

Repeated prompts may mean the workflow is underspecified; repeated broad approvals create permission debt. Allow frequent safe operations, ask on consequential transitions, deny prohibited action families, and audit persistent rules.

## CI control failure

If a required plugin/MCP/Hook/control cannot initialize, fail closed instead of silently skipping the control.
