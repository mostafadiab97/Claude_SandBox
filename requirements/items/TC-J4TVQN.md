---
id: TC-J4TVQN
type: test-case
title: "Verify: Mobile app limits the set point"
status: Approved
priority: Medium
owner: S. Adel
parent: INFO-J0FETE
order: 90
links:
  - type: verifies
    target: SYS-6FPGAZ
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Calibrate energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
