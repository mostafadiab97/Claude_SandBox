---
id: TC-W63TB3
type: test-case
title: "Regression: User account service synchronises humidity values"
status: Draft
priority: Medium
owner: Y. Saber
tags:
  - performance
  - i18n
  - power
parent: INFO-ECHASH
order: 610
links:
  - type: verifies
    target: SYS-J6RJYD
    confirmed: a893bb1c8e2d
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
