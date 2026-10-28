---
id: REQ-V477BQA
type: test-case
title: "Verify: Watchdog synchronises schedule entries"
status: Obsolete
priority: Low
owner: J. Müller
tags:
  - i18n
former-id: TC-K2BKV7
parent: REQ-K6FGAY0
order: b0y
links:
  - type: verifies
    target: REQ-3ZM1N85
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
