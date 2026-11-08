---
id: REQ-12ZQ7PT
type: test-case
title: "Verify: Rotary knob logs humidity values"
status: Draft
priority: High
owner: N. Kamal
tags:
  - safety
  - release-2.0
former-id: TC-90BRVV
parent: REQ-Y9VHHKA
order: b1N
links:
  - type: verifies
    target: REQ-YS5Z53S
    confirmed: 8c9ff96ed042
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Validate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
