---
id: TC-K46BEV
type: test-case
title: "Verify: Login screen encrypts the operating mode"
status: Approved
priority: High
parent: INFO-J0FETE
order: 1320
links:
  - type: verifies
    target: SYS-0N6C2D
    confirmed: 50615d725109
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
