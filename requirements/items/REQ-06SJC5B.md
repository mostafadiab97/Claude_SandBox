---
id: TC-HFBAB3
type: test-case
title: "Verify: Rotary knob restores safety limits"
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - release-2.0
parent: INFO-HTSZ15
order: 880
links:
  - type: verifies
    target: SYS-AE5DCT
    confirmed: 5733321e8c53
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Display error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
