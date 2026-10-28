---
id: REQ-E34NXP3
type: test-case
title: "Verify: Watchdog measures relay events"
status: Review
priority: High
owner: N. Kamal
tags:
  - safety
  - release-1.0
former-id: TC-4WZDA4
parent: REQ-K6FGAY0
order: a2
links:
  - type: verifies
    target: REQ-EJBN4HC
    confirmed: d3ae0a8a942d
  - type: verifies
    target: REQ-YNKMXPP
    confirmed: e0f62860c276
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Measure the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
