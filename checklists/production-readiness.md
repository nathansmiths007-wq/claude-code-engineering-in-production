# Production Readiness Checklist

## Before implementation

- [ ] problem and desired behavior are clear;
- [ ] repository owner/boundary identified;
- [ ] specification approved;
- [ ] acceptance criteria exist;
- [ ] verification owner identified;
- [ ] security/privacy impact reviewed;
- [ ] autonomy envelope written;
- [ ] base SHA and recovery state known.

## Before declaring implementation complete

- [ ] targeted tests pass;
- [ ] affected regression passes;
- [ ] oracle tests remain intact;
- [ ] final diff reviewed;
- [ ] no unexplained files;
- [ ] independent review complete;
- [ ] security review complete where required;
- [ ] remaining uncertainty stated.

## Before CI agent execution

- [ ] trusted trigger;
- [ ] ephemeral runner;
- [ ] explicit/bare configuration where appropriate;
- [ ] least-privilege credential;
- [ ] allowed tools explicit;
- [ ] required plugins/MCP validated;
- [ ] budget and timeout set;
- [ ] structured output schema defined;
- [ ] telemetry/privacy reviewed;
- [ ] failure path defined.

## Before deployment

- [ ] immutable artifact identified;
- [ ] CI corresponds to artifact commit;
- [ ] migration reviewed;
- [ ] staging healthy;
- [ ] rollback/forward-repair plan exists;
- [ ] security gate passed;
- [ ] production credentials isolated;
- [ ] explicit approval satisfied.
