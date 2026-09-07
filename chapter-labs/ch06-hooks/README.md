# Chapter 6 Lab — Hooks

**Starting tag:** `ch05-skills-ready`  
**Milestone:** `ch06-hooks-ready`

**Objective:** add deterministic guardrails at lifecycle boundaries.

## Deliverables
- one formatting or validation Hook
- one security/completion Hook
- `hook-test-matrix.md`

## Workflow
1. Select the exact Hook event and document its current blocking semantics.
2. Implement a small deterministic handler.
3. Test allowed input, prohibited input, malformed input, missing dependency, handler error, timeout, and malformed output.
4. Record whether each failure blocks, warns, or allows continuation.
5. Add observable logging without leaking sensitive content.

## Verification
The guardrail is complete only when the failure modes of the Hook itself are understood and tested.
