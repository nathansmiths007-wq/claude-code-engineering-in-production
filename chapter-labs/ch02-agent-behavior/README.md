# Chapter 2 Lab — Agent Behavior

**Objective:** observe the agentic loop and distinguish model judgment from tool execution and permission enforcement.

## Deliverables
- `agent-loop-notes.md`
- `tool-evidence.md`
- `permission-observations.md`

## Workflow
1. Give Claude a bounded read/diagnosis task.
2. Record each cycle of context gathering, tool selection, tool result, and next decision.
3. Interrupt once and steer the task without resetting the repository.
4. Compare a read-only run with one that requests mutation/testing authority.
5. Identify which controls live in prompts, which live in Claude Code, and which live outside Claude Code.

## Verification
You should be able to explain why fluent reasoning is not evidence, and why tools, permissions, and external system controls must be evaluated separately.
