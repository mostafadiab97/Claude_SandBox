---
id: TC-PVGMPC
type: test-case
title: "Regression: Heat pump driver measures firmware images"
status: Review
owner: Y. Saber
parent: INFO-ECHASH
order: 1070
links:
  - type: verifies
    target: SYS-3NA7W8
    confirmed: 303f8590e242
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
