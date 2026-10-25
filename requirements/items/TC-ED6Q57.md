---
id: TC-ED6Q57
type: test-case
title: "Verify: Power supply limits the set point"
status: Review
priority: Medium
tags:
  - power
  - release-1.0
  - ux
parent: INFO-MACGC3
order: 520
links:
  - type: verifies
    target: SYS-6VF733
---
**Objective:** verify that the power supply behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the power supply with default settings.
2. Display relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
