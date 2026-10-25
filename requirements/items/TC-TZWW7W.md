---
id: TC-TZWW7W
type: test-case
title: "Regression: Schedule editor encrypts energy consumption"
status: Obsolete
priority: High
owner: Y. Saber
parent: INFO-ECHASH
order: 1030
links:
  - type: verifies
    target: SYS-QKGZJJ
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
