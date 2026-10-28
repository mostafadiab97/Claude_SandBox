---
id: REQ-RJNZCRZ
type: test-case
title: "Verify: Power supply synchronises humidity values"
status: Approved
priority: Low
owner: R. Nabil
tags:
  - safety
  - cost
former-id: TC-W8Y56V
parent: REQ-F9Z1FYS
order: b03
links:
  - type: verifies
    target: REQ-Y7VXC9H
    confirmed: f8fcab8bd387
  - type: verifies
    target: REQ-0CW7N9N
    confirmed: 3119f0b6b4c8
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Synchronise the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
