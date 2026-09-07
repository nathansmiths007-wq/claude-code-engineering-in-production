# Chapter 11 Lab — Large Codebase Safety

**Starting state:** `ch09-plugin-ready` plus the completed Chapter 10 specification.

**Objective:** discover ownership, contracts, and blast radius before changing mature code.

## Deliverables
- `repository-map.md`
- `dependency-blast-radius.md`
- `modification-surface.md`

## Workflow
1. Map repository/package ownership and central service boundaries.
2. Identify generated, vendored, build, and no-touch areas.
3. Use layered instructions and path-scoped rules.
4. Combine text search, code intelligence, source, and tests to trace behavior.
5. Stop discovery when the authoritative implementation boundary and affected regression surface are known.
6. Prefer the smallest justified change.

## Verification
Every planned file should map to a requirement or dependency; unexpected edit surfaces require renewed investigation.
