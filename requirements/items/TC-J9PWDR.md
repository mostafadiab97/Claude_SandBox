---
id: TC-J9PWDR
type: test-case
title: "Verify: Bluetooth LE link restores relay events"
status: Approved
priority: Medium
owner: M. Farouk
parent: INFO-F0M7VC
order: 630
links:
  - type: verifies
    target: SYS-MY3DCX
    confirmed: ace85c596789
  - type: verifies
    target: SW-3GNB5A
    confirmed: 4b2f2da462f8
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Store the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
