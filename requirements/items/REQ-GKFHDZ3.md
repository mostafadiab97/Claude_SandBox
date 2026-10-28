---
id: REQ-GKFHDZ3
type: test-case
title: "Verify: Watchdog reports the operating mode"
status: Approved
priority: Medium
owner: K. Tanaka
former-id: TC-MC7AA5
parent: REQ-K6FGAY0
order: b0G
links:
  - type: verifies
    target: REQ-H6FFXS1
    confirmed: 179cd4fd7511
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
