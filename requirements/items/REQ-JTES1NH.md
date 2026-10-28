---
id: REQ-JTES1NH
type: test-case
title: "Verify: Rotary knob validates the connection state"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - regulatory
  - cost
former-id: TC-DPYT6F
parent: REQ-Y9VHHKA
order: b09
links:
  - type: verifies
    target: REQ-3EX8QAF
    confirmed: 2504ace2c747
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Display sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
