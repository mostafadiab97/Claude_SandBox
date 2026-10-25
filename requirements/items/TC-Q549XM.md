---
id: TC-Q549XM
type: test-case
title: "Verify: Rotary knob synchronises the set point"
status: Approved
priority: High
tags:
  - release-2.0
parent: INFO-HTSZ15
order: 1320
links:
  - type: verifies
    target: SYS-DJE020
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Encrypt energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
