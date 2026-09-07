# Chapter 14 Lab — Worktrees and Parallel Agents

**Starting tag:** `ch12-verification-ready`  
**Milestone:** `ch14-parallel-ready`

**Objective:** increase throughput without shared-state races.

## Deliverables
- worktree inventory
- shared-contract artifact
- structured handoffs
- integration evidence

## Workflow
1. Freeze the shared contract before parallel writes.
2. Give each editing worker a common base SHA and owned paths.
3. Use worktrees for filesystem isolation and separate runtime resources where needed.
4. Enforce one authoritative writer for shared contracts/files.
5. Integrate in dependency order, not completion order.
6. Re-run verification after composition.
7. Inject one overlapping-edit collision and document the recovery.

## Verification
Parallel work is successful only if integrated defects/rework do not erase the time saved.
