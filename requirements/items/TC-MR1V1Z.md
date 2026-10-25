---
id: TC-MR1V1Z
type: test-case
title: "Verify: Rotary knob notifys the set point"
status: Draft
priority: Low
owner: Y. Saber
parent: INFO-HTSZ15
order: 210
links:
  - type: verifies
    target: SYS-CABT71
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Authenticate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
