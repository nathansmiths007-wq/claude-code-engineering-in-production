# Chapter 4 Lab — Project Memory and Instructions

**Milestone:** `ch04-context-ready`

**Objective:** engineer durable project instructions without turning the root context into a manual.

## Deliverables
- root `CLAUDE.md`
- package-level instruction example
- `.claude/rules/` path-scoped example
- `instruction-resolution.md`

## Workflow
1. Put repository-wide architecture, verification, security, and recovery rules in a concise root file.
2. Move package conventions into nested/project-specific guidance.
3. Add at least one path-scoped rule for a sensitive subsystem.
4. Test tasks from different directories and record which instruction layers apply.
5. Remove any instruction that is merely historical conversation rather than durable project truth.

## Verification
Instructions should be discoverable, non-contradictory, scoped, and cheap enough to load repeatedly.
