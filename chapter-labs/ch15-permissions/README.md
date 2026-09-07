# Chapter 15 Lab — Permissions, Sandboxing, and Autonomy

**Starting tag:** `ch14-parallel-ready`

**Objective:** build a task-specific autonomy envelope and distinguish permission policy from execution isolation.

## Deliverables
- `autonomy-envelope.md`
- permission matrix
- sandbox observations
- recovery notes

## Workflow
1. Classify needed actions as Allow, Ask, or Deny.
2. Protect sensitive/control-plane paths and deny production credentials/systems.
3. Run the same safe shell action with and without sandboxing and record the difference.
4. Test a denied action and an unknown action in the selected headless/interactive posture.
5. Map the task to L0–L9 and state what verification is required before moving higher.

## Verification
Authority should be no broader than necessary, unknown consequential actions should fail safely, and recovery must match the state that can change.
