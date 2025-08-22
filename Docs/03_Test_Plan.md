# Test Plan – Insurance Policy & Claims Portal

## Goal
Make sure the portal works for policies, payments, and claims without breaking anything.

## In Scope
- Policy: quote, bind, issue, endorse, renew, cancel
- Billing: take payment, refund
- Claims: FNOL, assign, evaluate, close

## Out of Scope
- Performance testing
- Integrations not listed here

## Test Types
- Functional, Regression, UAT, Basic API checks

## Environments
- App: Training/Sandbox
- Browser: Chrome (latest)
- Test Data: see /Sample_Data files

## Entry/Exit
- Entry: environment ready, test data loaded
- Exit: critical defects fixed or deferred by BA

## Roles
- You (QA/BA): write and run tests, log defects, report status

## Schedule (example)
- Day 1: Setup + Stories + RTM
- Day 2: Test cases
- Day 3–4: Execute + Defects
- Day 5: UAT + Reports
