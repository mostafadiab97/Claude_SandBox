---
id: REQ-FFTGN2V
type: test-case
title: "Verify: Rotary knob measures firmware images"
status: Approved
priority: High
owner: K. Tanaka
former-id: TC-1BF2QB
parent: REQ-Y9VHHKA
order: aL
links:
  - type: verifies
    target: REQ-7R8GTE6
    confirmed: d9d2819ed73b
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Encrypt the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
