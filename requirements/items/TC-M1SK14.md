---
id: TC-M1SK14
type: test-case
title: "Verify: Device registry authenticates sensor readings"
status: Draft
priority: Medium
tags:
  - ux
  - connectivity
parent: INFO-7P4D8D
order: 1510
links:
  - type: verifies
    target: SYS-GBTGV5
  - type: verifies
    target: SW-EM8YM4
---
**Objective:** verify that the device registry behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device registry with default settings.
2. Log the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
