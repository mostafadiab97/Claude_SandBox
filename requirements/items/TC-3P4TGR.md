---
id: TC-3P4TGR
type: test-case
title: "Verify: Rotary knob calibrates the connection state"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - cost
  - ux
parent: INFO-HTSZ15
order: 580
links:
  - type: verifies
    target: SYS-H2ZXTG
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Limit access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
