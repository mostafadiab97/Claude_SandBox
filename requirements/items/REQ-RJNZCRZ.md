---
id: TC-W8Y56V
type: test-case
title: "Verify: Power supply synchronises humidity values"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - safety
  - cost
parent: INFO-MACGC3
order: 660
links:
  - type: verifies
    target: SYS-BP947W
    confirmed: f8fcab8bd387
  - type: verifies
    target: SW-A00Y82
    confirmed: 3119f0b6b4c8
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Synchronise the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
