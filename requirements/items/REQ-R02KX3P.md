---
id: TC-9XSRQX
type: test-case
title: "Regression: Bluetooth LE link measures sensor readings"
status: Obsolete
priority: Medium
parent: INFO-ECHASH
order: 1920
links:
  - type: verifies
    target: SYS-34QNYE
    confirmed: f6e72f885951
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
