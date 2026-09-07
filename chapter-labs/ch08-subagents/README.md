# Chapter 8 Lab — Subagents

**Starting tag:** `ch07-mcp-ready`  
**Milestone:** `ch08-agents-ready`

**Objective:** delegate for specialization, context isolation, and authority reduction rather than merely for parallelism.

## Deliverables
- Explorer
- Planner
- Developer
- Tester
- Reviewer
- Security Reviewer
- `agent-authority-matrix.md`

## Workflow
1. Give every role a narrow objective, tool/permission set, output contract, and stop condition.
2. Run Explorer and Planner on a bounded change before allowing edits.
3. Run Developer in an isolated workspace.
4. Give Tester/Reviewer the specification, diff, and evidence—not the Developer's confidence narrative.
5. Compare findings between the implementation lineage and fresh-context reviewers.

## Verification
Independent roles should reveal different risks while preventing implementers from grading themselves.
