---
id: TC-TQM1JF
type: test-case
title: "Regression: Main PCB displays sensor readings"
status: Review
priority: Medium
parent: INFO-ECHASH
order: 1040
links:
  - type: verifies
    target: SYS-80ZJ33
    confirmed: 7a5b090e57ac
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
