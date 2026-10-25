---
id: TC-M4PZA5
type: test-case
title: "Verify: Watchdog measures relay events"
status: Approved
priority: Medium
tags:
  - safety
  - ux
parent: INFO-Z4TW4B
order: 1270
links:
  - type: verifies
    target: SYS-XJ8215
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Notify the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
