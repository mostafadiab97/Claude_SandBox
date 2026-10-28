---
id: TC-Y6Q125
type: test-case
title: "Verify: Schedule editor reports the set point"
status: Review
priority: High
owner: L. Samir
tags:
  - regulatory
  - power
  - cost
parent: INFO-J0FETE
order: 70
links:
  - type: verifies
    target: SYS-HPT8TA
    confirmed: 55ed01be7cc1
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Notify relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
