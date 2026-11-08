---
id: REQ-NBRKN5S
type: test-case
title: "Verify: Watchdog authenticates the set point"
status: Approved
priority: Medium
owner: É. Laurent
former-id: TC-0EKP51
parent: REQ-K6FGAY0
order: b1R
links:
  - type: verifies
    target: REQ-BS6TC1D
    confirmed: 6b7714cc0542
  - type: verifies
    target: REQ-7HQPYPJ
    confirmed: 728d60341efa
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Detect sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
