# Chapter 18 Lab — Observable CI Automation

**Starting state:** `ch16-secure-ready` plus completed Chapter 17 recovery state.  
**Milestone:** `ch18-ci-ready`

**Objective:** build a bounded headless Claude Code workflow that produces machine-readable evidence and fails closed.

## Deliverables
- `automation-contract.md`
- CI-specific settings
- JSON result schema
- budget/timeout policy
- harness validation
- telemetry/privacy plan
- CI completion gate
- recovery evidence

## Workflow
1. Define trusted/untrusted inputs and a read-only or bounded implementation task.
2. Run with explicit/bare configuration where supported.
3. Validate required plugin/MCP/tool startup state.
4. Enforce cost and time limits.
5. Capture structured results, deterministic tests, diff evidence, and telemetry.
6. Run an independent verifier/fresh-context review.
7. Fail if scope, verification, budget, security, or control-plane requirements are violated.
8. Inject a missing-control failure and recover using Chapter 17.

## Verification
The orchestrator—not the agent's prose—must own the final success decision.
