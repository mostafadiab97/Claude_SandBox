---
id: TC-05WBNN
type: test-case
title: "Regression: Schedule editor stores the set point"
status: Draft
priority: Low
tags:
  - connectivity
parent: INFO-ECHASH
order: 1650
links:
  - type: verifies
    target: SYS-ZNDMZ4
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
