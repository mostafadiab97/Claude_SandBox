---
id: TC-MC7AA5
type: test-case
title: "Verify: Watchdog reports the operating mode"
status: Approved
priority: Medium
owner: K. Tanaka
parent: INFO-Z4TW4B
order: 790
links:
  - type: verifies
    target: SYS-RT7J5E
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Calibrate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
