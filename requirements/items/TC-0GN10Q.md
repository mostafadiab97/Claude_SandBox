---
id: TC-0GN10Q
type: test-case
title: "Regression: Login screen switchs firmware images"
status: Approved
priority: High
owner: M. Farouk
tags:
  - connectivity
  - safety
  - accessibility
parent: INFO-ECHASH
order: 1450
links:
  - type: verifies
    target: SYS-HC7415
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Encrypt the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
