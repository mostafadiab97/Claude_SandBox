---
id: REQ-56FPV4M
type: test-case
title: "Verify: Rotary knob stores safety limits"
status: Review
priority: High
owner: A. Hassan
tags:
  - release-2.0
former-id: TC-D1BZHN
parent: REQ-Y9VHHKA
order: ak
links:
  - type: verifies
    target: REQ-8HJX710
    confirmed: 6d2e8325363f
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Measure relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
