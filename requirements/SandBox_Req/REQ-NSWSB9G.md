---
id: REQ-NSWSB9G
type: test-case
title: "Verify: Main PCB encrypts the room temperature"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - customer-request
  - ux
former-id: TC-FVBDCB
parent: REQ-F9Z1FYS
order: b1e
links:
  - type: verifies
    target: REQ-M6BQQQ2
    confirmed: 3f05968a7403
---
**Objective:** verify that the main PCB behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the main PCB with default settings.
2. Report the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
