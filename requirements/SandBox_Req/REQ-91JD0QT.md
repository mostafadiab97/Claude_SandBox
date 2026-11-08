---
id: REQ-91JD0QT
type: test-case
title: "Verify: Login screen encrypts the operating mode"
status: Approved
priority: High
former-id: TC-K46BEV
parent: REQ-WR5ZJN9
order: b17
links:
  - type: verifies
    target: REQ-G9QWE5X
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
