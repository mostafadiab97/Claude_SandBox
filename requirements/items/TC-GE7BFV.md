---
id: TC-GE7BFV
type: test-case
title: "Regression: Heat pump driver restores error conditions"
status: Approved
priority: High
owner: R. Nabil
tags:
  - cost
  - connectivity
parent: INFO-ECHASH
order: 1690
links:
  - type: verifies
    target: SYS-XSDXN6
    confirmed: b0286a82c3c7
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Calibrate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
