---
id: REQ-SEA9YEZ
type: test-case
title: "Verify: Watchdog reports energy consumption"
status: Review
priority: High
owner: محمد علي
tags:
  - customer-request
former-id: TC-XWDH08
parent: REQ-K6FGAY0
order: b1M
links:
  - type: verifies
    target: REQ-33MFB68
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
