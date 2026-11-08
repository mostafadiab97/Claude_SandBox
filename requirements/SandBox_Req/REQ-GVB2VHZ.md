---
id: REQ-GVB2VHZ
type: test-case
title: "Verify: Rotary knob encrypts schedule entries"
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - release-1.0
  - cost
former-id: TC-1QT8P5
parent: REQ-Y9VHHKA
order: a5
links:
  - type: verifies
    target: REQ-VFTA3G4
    confirmed: 75c4df8a465f
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Authenticate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
