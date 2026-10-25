---
id: TC-6VRMEA
type: test-case
title: "Verify: Schedule editor stores user preferences"
status: Approved
priority: High
owner: R. Nabil
tags:
  - ux
  - release-1.0
  - power
parent: INFO-J0FETE
order: 200
links:
  - type: verifies
    target: SYS-JYEJXF
---
**Objective:** verify that the schedule editor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the schedule editor with default settings.
2. Calibrate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
