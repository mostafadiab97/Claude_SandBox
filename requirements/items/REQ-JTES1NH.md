---
id: TC-DPYT6F
type: test-case
title: "Verify: Rotary knob validates the connection state"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - regulatory
  - cost
parent: INFO-HTSZ15
order: 720
links:
  - type: verifies
    target: SYS-Q83WR4
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
