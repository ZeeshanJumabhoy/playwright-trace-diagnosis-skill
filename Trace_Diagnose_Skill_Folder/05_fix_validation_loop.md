# Phase 5 – Controlled Fix Validation

## Rule
Maximum 2 retry cycles per test case.

## Process
1. Apply fix
2. Re-run test
3. If pass → Mark resolved
4. If fail → Retry once more
5. If still failing → Mark Manual Review Required

Never allow infinite loops.
