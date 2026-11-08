---
id: REQ-2RK36P2
type: test-case
title: "Verify: Rotary knob authenticates energy consumption"
status: Draft
priority: Low
owner: L. Samir
former-id: TC-97A80Y
parent: REQ-Y9VHHKA
order: b0J
links:
  - type: verifies
    target: REQ-9VNZEQ9
    confirmed: f1e98774112c
  - type: verifies
    target: REQ-Y9EE2KF
    confirmed: ce7723cdc2d3
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Report sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
