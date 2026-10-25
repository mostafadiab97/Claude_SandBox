---
id: TC-BCF908
type: test-case
title: "Verify: Rotary knob measures audit records"
status: Approved
priority: High
owner: A. Hassan
tags:
  - power
  - safety
parent: INFO-HTSZ15
order: 730
links:
  - type: verifies
    target: SYS-CQEWAD
  - type: verifies
    target: SW-XD35BZ
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
