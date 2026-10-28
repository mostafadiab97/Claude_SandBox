---
id: REQ-FBNKVE9
type: test-case
title: "Verify: Watchdog measures relay events"
status: Approved
priority: Medium
tags:
  - safety
  - ux
former-id: TC-M4PZA5
parent: REQ-K6FGAY0
order: b12
links:
  - type: verifies
    target: REQ-G8523S3
    confirmed: 56e95d4cfbe7
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Notify the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
