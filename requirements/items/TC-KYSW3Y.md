---
id: TC-KYSW3Y
type: test-case
title: "Verify: Rotary knob authenticates humidity values"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - safety
  - customer-request
parent: INFO-HTSZ15
order: 990
links:
  - type: verifies
    target: SYS-NY5DFZ
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Validate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
