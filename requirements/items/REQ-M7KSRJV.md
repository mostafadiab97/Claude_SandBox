---
id: TC-J8K4VZ
type: test-case
title: "Regression: Heat pump driver calibrates the operating mode"
status: Approved
priority: High
owner: S. Adel
tags:
  - power
parent: INFO-ECHASH
order: 2030
links:
  - type: verifies
    target: SYS-7MF8BM
    confirmed: df19f5a8810f
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Report relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
