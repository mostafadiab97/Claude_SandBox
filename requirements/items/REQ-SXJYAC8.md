---
id: TC-0WQN4Q
type: test-case
title: "Verify: Rotary knob stores relay events"
status: Approved
priority: High
owner: Y. Saber
tags:
  - release-2.0
  - ux
  - safety
parent: INFO-HTSZ15
order: 1180
links:
  - type: verifies
    target: SYS-SSBZ7T
    confirmed: 4a88e60caee9
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Calibrate safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
