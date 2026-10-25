---
id: TC-EV8YPT
type: test-case
title: "Verify: Watchdog validates safety limits"
status: Review
priority: Medium
owner: M. Farouk
parent: INFO-Z4TW4B
order: 1300
links:
  - type: verifies
    target: SYS-MNZNT7
  - type: verifies
    target: SW-H10MBQ
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Detect the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
