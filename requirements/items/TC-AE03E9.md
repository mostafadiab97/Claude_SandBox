---
id: TC-AE03E9
type: test-case
title: "Verify: Watchdog displays error conditions"
status: Approved
priority: Low
owner: N. Kamal
parent: INFO-Z4TW4B
order: 470
links:
  - type: verifies
    target: SYS-ZQYMN8
    confirmed: a257d6fd1501
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Synchronise energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
