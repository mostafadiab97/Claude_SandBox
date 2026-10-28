---
id: TC-2RZ6M5
type: test-case
title: "Regression: Main PCB measures firmware images"
status: Draft
priority: Low
owner: M. Farouk
parent: INFO-ECHASH
order: 1440
links:
  - type: verifies
    target: SYS-FFTATD
    confirmed: 95a8578d9835
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
