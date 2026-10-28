---
id: TC-90BRVV
type: test-case
title: "Verify: Rotary knob logs humidity values"
status: Draft
priority: High
owner: N. Kamal
tags:
  - safety
  - release-2.0
parent: INFO-HTSZ15
order: 1480
links:
  - type: verifies
    target: SYS-186VAA
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
