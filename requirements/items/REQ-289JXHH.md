---
id: REQ-289JXHH
type: test-case
title: "Verify: Watchdog encrypts user preferences"
status: Approved
priority: High
owner: محمد علي
tags:
  - safety
  - cost
  - security
former-id: TC-HGC5N5
parent: REQ-K6FGAY0
order: b04
links:
  - type: verifies
    target: REQ-5CZT8BT
    confirmed: 7750ef7b4cd4
  - type: verifies
    target: REQ-AY0W4FN
    confirmed: fbc7895c16c0
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Restore access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
