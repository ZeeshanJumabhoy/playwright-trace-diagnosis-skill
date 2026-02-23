# Phase 2 – Error Understanding

## Objective
Interpret the error message contextually.

## Evaluate
- Timeout
- Locator not found
- Multiple elements found
- waitForResponse timeout
- Assertion mismatch
- Navigation crash

## Special Handling
- If toast expected but not found → inspect console + try/catch logic
- If API wait failure → inspect network response
- If locator strict mode error → inspect duplicates
- If data missing → inspect response payload

## Output
- Technical failure explanation
- Contextual reason
