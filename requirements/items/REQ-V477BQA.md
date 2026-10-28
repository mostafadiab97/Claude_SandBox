---
id: TC-K2BKV7
type: test-case
title: "Verify: Watchdog synchronises schedule entries"
status: Obsolete
priority: Low
owner: J. Müller
tags:
  - i18n
parent: INFO-Z4TW4B
order: 1230
links:
  - type: verifies
    target: SYS-RGCFDP
    confirmed: 703711cfcecf
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Restore error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
