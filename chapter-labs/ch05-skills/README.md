# Chapter 5 Lab — Skills

**Starting tag:** `ch04-context-ready`  
**Milestone:** `ch05-skills-ready`

**Objective:** turn a repeated engineering procedure into a reusable Skill.

## Deliverables
- one Skill directory with `SKILL.md`
- `skill-invocation-notes.md`
- `skill-failure-test.md`

## Workflow
1. Choose a repeatable procedure such as release check, test suite, migration review, or incident analysis.
2. Define objective, preconditions, required context, allowed tools, ordered steps, evidence, failure behavior, and stop condition.
3. Run the Skill on a valid task and on a task missing a prerequisite.
4. Confirm the Skill does not silently grant broader authority than the task needs.

## Verification
The procedure should produce consistent evidence across runs while remaining scoped and auditable.
