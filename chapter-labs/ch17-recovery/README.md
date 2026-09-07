# Chapter 17 Lab — Failure, Recovery, and Rollback

**Starting tag:** `ch16-secure-ready`

**Objective:** recover using the system that actually owns the damaged state.

## Deliverables
- `recovery-layers.md`
- incident notes for each injection
- `iteration-policy.md`
- recovery Skill
- final recovery matrix

## Failure injections
- wrong direct edit;
- Bash-owned file change;
- stale context;
- hallucinated interface;
- test manipulation;
- parallel collision;
- excessive authority;
- external side effect;
- credential incident;
- runaway iteration.

For each use: **Contain → Classify → Recover → Verify → Prevent Recurrence**.

## Verification
Demonstrate which failures are handled by rewind/checkpoints, Git, deployment rollback, data recovery, credential revocation/rotation, or compensating action. Never treat Git as universal rollback.
