# Autonomy Envelope

## Task / Change Class

## Autonomy Level

L0–L9 from the book's Autonomy Ladder.

## Allowed

- read approved repository scope;
- edit owned worktree paths;
- run approved deterministic checks.

## Ask

List legitimate but consequential operations, for example dependency installation, Git push, new MCP, or control-plane changes.

## Deny

List prohibited actions, for example protected-branch push, production database, production credentials, production deployment, or secret files.

## Sandbox / Isolation

- filesystem boundary;
- network boundary;
- worktree;
- container/VM if needed.

## Verification

What evidence must exist before authority can increase?

## Recovery

What system owns restoration if the action is wrong?

## Human Approval Gates

Which transitions remain human-controlled?
