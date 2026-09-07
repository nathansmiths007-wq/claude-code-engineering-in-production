# Chapter 3 Lab — Context Engineering

**Objective:** build a task-specific context funnel and measure the effect of irrelevant or stale context.

## Deliverables
- `context-map.md`
- `context-budget.md`
- `pollution-observations.md`

## Workflow
1. Start from the narrowest repository location that can answer the task.
2. Add only files, contracts, tests, and decisions that can change the engineering decision.
3. Record what was loaded and why.
4. Repeat with deliberately noisy context such as unrelated logs, old plans, or broad repository dumps.
5. Compare reasoning quality, time, tool usage, and token/context pressure.

## Verification
A useful context set should be smaller, current, and directly connected to the decision; the polluted run should demonstrate why more context is not automatically better.
