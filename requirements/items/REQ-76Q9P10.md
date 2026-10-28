---
id: TC-HZ0FQ8
type: test-case
title: "Regression: Menu system detects the connection state"
status: Draft
priority: Low
owner: N. Kamal
tags:
  - safety
  - cost
parent: INFO-ECHASH
order: 2110
links:
  - type: verifies
    target: SYS-8J1N3D
    confirmed: b357a6a8ec1a
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Restore the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
