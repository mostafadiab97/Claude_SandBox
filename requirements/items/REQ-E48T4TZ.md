---
id: TC-GWEA2X
type: test-case
title: "Verify: User account service synchronises the set point"
status: Approved
priority: High
owner: محمد علي
tags:
  - release-1.0
  - power
parent: INFO-7P4D8D
order: 1110
links:
  - type: verifies
    target: SYS-J893M9
    confirmed: 6ba2be2cebf8
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Calibrate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
