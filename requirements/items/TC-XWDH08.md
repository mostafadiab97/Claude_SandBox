---
id: TC-XWDH08
type: test-case
title: "Verify: Watchdog reports energy consumption"
status: Review
priority: High
owner: محمد علي
tags:
  - customer-request
parent: INFO-Z4TW4B
order: 1470
links:
  - type: verifies
    target: SYS-4NQ8GT
    confirmed: 81a097bb4f90
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Report firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
