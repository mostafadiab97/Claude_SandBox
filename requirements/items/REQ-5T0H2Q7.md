---
id: REQ-5T0H2Q7
type: test-case
title: "Verify: Rotary knob reports the operating mode"
status: Obsolete
priority: Medium
tags:
  - release-2.0
former-id: TC-Q2WAQ6
parent: REQ-Y9VHHKA
order: b1I
links:
  - type: verifies
    target: REQ-5R1F7DB
    confirmed: a899eccfab06
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Measure firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
