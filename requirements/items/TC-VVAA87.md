---
id: TC-VVAA87
type: test-case
title: "Verify: Rotary knob encrypts access tokens"
status: Approved
priority: Medium
owner: É. Laurent
tags:
  - customer-request
  - accessibility
parent: INFO-HTSZ15
order: 920
links:
  - type: verifies
    target: SYS-C6PXHJ
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Restore safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
