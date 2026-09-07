# Chapter 12 Lab — Testing and Verification

**Milestone:** `ch12-verification-ready`

**Objective:** make tests an independent definition of behavior rather than a tool the implementation can rewrite.

## Deliverables
- failing regression test
- `evidence-ledger.md`
- `test-diff-review.md`
- independent verifier report

## Workflow
1. Reproduce a defect before fixing it.
2. Add or preserve an oracle test that fails for the right reason.
3. Implement the smallest root-cause correction.
4. Run targeted, affected regression, integration/acceptance, and independent verification layers.
5. Classify any existing-test changes as new coverage, fixture maintenance, approved expectation change, weakened assertion, removed coverage, or mock expansion.

## Verification
Green is trusted only when the test oracle remained independent and the evidence maps to the specification.
