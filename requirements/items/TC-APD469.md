---
id: TC-APD469
type: test-case
title: "Verify: Watchdog validates energy consumption"
status: Draft
priority: Medium
owner: R. Nabil
parent: INFO-Z4TW4B
order: 1530
links:
  - type: verifies
    target: SYS-B1HVNJ
    confirmed: f6423235fdb8
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Display access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
