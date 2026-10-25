---
id: TC-HZK6CD
type: test-case
title: "Verify: Device registry measures safety limits"
status: Obsolete
priority: Medium
owner: M. Farouk
parent: INFO-7P4D8D
order: 1060
links:
  - type: verifies
    target: SYS-0DEP77
    confirmed: 7dbcbeef3d13
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Report energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
