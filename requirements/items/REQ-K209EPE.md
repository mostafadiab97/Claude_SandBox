---
id: REQ-K209EPE
type: test-case
title: "Verify: Battery backup authenticates sensor readings"
status: Approved
priority: High
owner: M. Farouk
former-id: TC-V3AMV5
parent: REQ-F9Z1FYS
order: az
links:
  - type: verifies
    target: REQ-TT5358R
    confirmed: 3cc57eda9250
---
**Objective:** verify that the battery backup behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the battery backup with default settings.
2. Notify the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
