---
id: TC-KFWNAJ
type: test-case
title: "Verify: Rotary knob reports sensor readings"
status: Review
priority: High
owner: M. Farouk
tags:
  - power
  - ux
  - cost
parent: INFO-HTSZ15
order: 1290
links:
  - type: verifies
    target: SYS-BRW2HG
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Synchronise the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
