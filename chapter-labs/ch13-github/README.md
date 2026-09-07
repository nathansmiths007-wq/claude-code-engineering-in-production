# Chapter 13 Lab — Git, GitHub, and Pull Requests

**Starting tag:** `ch12-verification-ready`

**Objective:** turn a verified local change into a bounded, attributable, reviewable, reversible delivery artifact.

## Deliverables
- feature branch
- coherent commits
- structured PR description
- independent review evidence
- CI evidence

## Workflow
1. Keep branch scope aligned with the specification.
2. Inspect status, diff, diff-check, and staged diff before commit.
3. Use commits as engineering ideas rather than model narration.
4. Build traceability from issue → spec → branch → commit → PR → verification.
5. Use least-privilege GitHub Actions and treat issue/PR text as untrusted input.
6. Keep merge authority separate from implementation.

## Verification
CI must evaluate the agent's actual commit and the PR must make scope, tests, security, migration, and remaining uncertainty visible.
