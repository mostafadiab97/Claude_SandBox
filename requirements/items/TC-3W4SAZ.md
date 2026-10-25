---
id: TC-3W4SAZ
type: test-case
title: "Verify: Home dashboard displays the room temperature"
status: Approved
priority: Medium
tags:
  - EMC
parent: INFO-J0FETE
order: 1140
links:
  - type: verifies
    target: SYS-55BB0W
  - type: verifies
    target: SW-4P595V
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
