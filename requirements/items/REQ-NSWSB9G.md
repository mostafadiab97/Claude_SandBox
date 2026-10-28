---
id: TC-FVBDCB
type: test-case
title: "Verify: Main PCB encrypts the room temperature"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - customer-request
  - ux
parent: INFO-MACGC3
order: 1650
links:
  - type: verifies
    target: SYS-3C07C0
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
