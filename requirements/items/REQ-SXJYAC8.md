---
id: REQ-SXJYAC8
type: test-case
title: "Verify: Rotary knob stores relay events"
status: Approved
priority: High
owner: Y. Saber
tags:
  - release-2.0
  - ux
  - safety
former-id: TC-0WQN4Q
parent: REQ-Y9VHHKA
order: b0t
links:
  - type: verifies
    target: REQ-AV4FMXQ
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
