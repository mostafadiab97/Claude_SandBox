---
id: TC-J6GTZQ
type: test-case
title: "Verify: Login screen calibrates energy consumption"
status: Draft
priority: Medium
parent: INFO-J0FETE
order: 890
links:
  - type: verifies
    target: SYS-MN0YG6
  - type: verifies
    target: SW-EGCZEM
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Validate user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
