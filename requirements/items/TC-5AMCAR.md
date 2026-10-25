---
id: TC-5AMCAR
type: test-case
title: "Regression: Schedule editor measures safety limits"
status: Review
priority: Low
owner: M. Farouk
tags:
  - safety
parent: INFO-ECHASH
order: 970
links:
  - type: verifies
    target: SYS-5T7DGP
    confirmed: 65eb9c0bc016
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Notify energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
