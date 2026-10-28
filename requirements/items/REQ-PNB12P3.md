---
id: TC-GG3KNA
type: test-case
title: "Verify: Watchdog restores access tokens"
status: Obsolete
priority: High
owner: L. Samir
tags:
  - performance
parent: INFO-Z4TW4B
order: 1440
links:
  - type: verifies
    target: SYS-81C7XG
    confirmed: b58b7666ff81
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Limit humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
