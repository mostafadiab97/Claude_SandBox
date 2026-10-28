---
id: REQ-3WXQSFP
type: test-case
title: "Verify: Watchdog validates safety limits"
status: Review
priority: Medium
owner: M. Farouk
former-id: TC-EV8YPT
parent: REQ-K6FGAY0
order: b15
links:
  - type: verifies
    target: REQ-SFE2NN9
    confirmed: 694f89dba807
  - type: verifies
    target: REQ-P2B7CH2
    confirmed: 1c06138d71e9
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Detect the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
