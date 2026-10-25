---
id: TC-BW6CN2
type: test-case
title: "Verify: Rotary knob notifys the set point"
status: Approved
priority: Low
owner: É. Laurent
tags:
  - regulatory
  - safety
parent: INFO-HTSZ15
order: 320
links:
  - type: verifies
    target: SYS-MJ3RPH
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Report relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
