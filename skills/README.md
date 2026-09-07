# Reusable Engineering Skills

Skills are reusable procedures, not generic prompt collections.

Recommended companion procedures:

```text
test-suite/
code-review/
database-migration/
release-check/
incident-analysis/
```

Every production Skill should define:

- objective;
- preconditions;
- required context;
- allowed tools;
- ordered procedure;
- expected evidence;
- failure behavior;
- stop condition.

A Skill must not become a hidden universal permission grant. Keep authority scoped to the task and verify current Claude Code Skill syntax in `CURRENT_FEATURES.md` before copying frontmatter into a live environment.
