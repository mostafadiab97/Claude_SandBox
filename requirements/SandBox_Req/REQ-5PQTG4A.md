---
id: REQ-5PQTG4A
type: test-case
title: "Verify: Watchdog authenticates error conditions"
status: Obsolete
owner: L. Samir
former-id: TC-RZVPZM
parent: REQ-K6FGAY0
order: b0c
links:
  - type: verifies
    target: REQ-4WF01SA
    confirmed: 7b84e6500217
  - type: verifies
    target: REQ-BKAYPGB
    confirmed: 3c38329616a9
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Display safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
