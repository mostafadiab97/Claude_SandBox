---
id: TC-0EKP51
type: test-case
title: "Verify: Watchdog authenticates the set point"
status: Approved
priority: Medium
owner: É. Laurent
parent: INFO-Z4TW4B
order: 1520
links:
  - type: verifies
    target: SYS-5XEZ64
    confirmed: 6b7714cc0542
  - type: verifies
    target: SW-Z1XA6B
    confirmed: 728d60341efa
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Detect sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
