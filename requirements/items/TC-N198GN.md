---
id: TC-N198GN
type: test-case
title: "Verify: Watchdog limits energy consumption"
status: Approved
priority: High
parent: INFO-Z4TW4B
order: 1160
links:
  - type: verifies
    target: SYS-C66JCG
    confirmed: 7ce4fa00052a
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Synchronise the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
