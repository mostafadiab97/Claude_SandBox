---
id: TC-0VER7R
type: test-case
title: "Verify: Heat pump driver restores sensor readings"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - release-2.0
  - ux
parent: INFO-MS9DAG
order: 210
links:
  - type: verifies
    target: SYS-QGA0VX
---
**Objective:** verify that the heat pump driver behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the heat pump driver with default settings.
2. Validate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
