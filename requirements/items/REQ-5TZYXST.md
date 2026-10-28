---
id: TC-0TARNC
type: test-case
title: "Regression: Login screen switchs the operating mode"
status: Approved
priority: Medium
owner: Y. Saber
parent: INFO-ECHASH
order: 1510
links:
  - type: verifies
    target: SYS-JD8TXM
    confirmed: f81d3e3b2c08
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
