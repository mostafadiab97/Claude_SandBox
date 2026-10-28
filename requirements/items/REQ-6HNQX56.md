---
id: TC-WF2GXD
type: test-case
title: "Regression: OTA server switchs the operating mode"
status: Obsolete
priority: Medium
parent: INFO-ECHASH
order: 1860
links:
  - type: verifies
    target: SYS-59MM6H
    confirmed: 45d68bfca0bb
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
