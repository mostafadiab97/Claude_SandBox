---
id: TC-F9PJXY
type: test-case
title: "Verify: Rotary knob logs user preferences"
status: Approved
priority: Low
owner: É. Laurent
tags:
  - security
  - regulatory
parent: INFO-HTSZ15
order: 1340
links:
  - type: verifies
    target: SYS-7BE6SJ
  - type: verifies
    target: SW-GT5SKH
---
**Objective:** verify that the rotary knob behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the rotary knob with default settings.
2. Measure the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
