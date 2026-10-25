---
id: TC-C9F5TJ
type: test-case
title: "Verify: Watchdog switchs safety limits"
status: Review
priority: High
owner: H. Mostafa
tags:
  - i18n
parent: INFO-Z4TW4B
order: 490
links:
  - type: verifies
    target: SYS-CFWA46
  - type: verifies
    target: SW-T6K42M
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Synchronise user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
