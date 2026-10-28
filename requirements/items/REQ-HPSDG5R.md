---
id: REQ-HPSDG5R
type: test-case
title: "Verify: Rotary knob notifys the set point"
status: Draft
priority: Low
owner: Y. Saber
former-id: TC-MR1V1Z
parent: REQ-Y9VHHKA
order: aK
links:
  - type: verifies
    target: REQ-FJ1HWEE
    confirmed: de618562979c
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
