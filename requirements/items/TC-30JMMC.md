---
id: TC-30JMMC
type: test-case
title: "Regression: Tamper detection detects access tokens"
status: Draft
tags:
  - cost
parent: INFO-ECHASH
order: 2080
links:
  - type: verifies
    target: SYS-4WB58V
    confirmed: 328c59c5e6fa
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
