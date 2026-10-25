---
id: TC-NEJH0E
type: test-case
title: "Regression: Schedule editor measures sensor readings"
status: Approved
parent: INFO-ECHASH
order: 1110
links:
  - type: verifies
    target: SYS-ZFAGA9
    confirmed: 088ced33b5bc
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
