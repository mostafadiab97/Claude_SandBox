---
id: REQ-EMKHQWH
type: test-case
title: "Verify: Rotary knob measures audit records"
status: Approved
priority: High
owner: A. Hassan
tags:
  - power
  - safety
former-id: TC-BCF908
parent: REQ-Y9VHHKA
order: b0A
links:
  - type: verifies
    target: REQ-89EGSYK
    confirmed: 2cb413be1ed1
  - type: verifies
    target: REQ-EMATTKB
    confirmed: 2a84ec4789f1
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Limit schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
