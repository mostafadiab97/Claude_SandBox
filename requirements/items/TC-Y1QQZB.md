---
id: TC-Y1QQZB
type: test-case
title: "Regression: Watchdog authenticates error conditions"
status: Review
tags:
  - i18n
  - connectivity
  - ux
parent: INFO-ECHASH
order: 1390
links:
  - type: verifies
    target: SYS-KH549P
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
