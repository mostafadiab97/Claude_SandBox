---
id: REQ-PNB12P3
type: test-case
title: "Verify: Watchdog restores access tokens"
status: Obsolete
priority: High
owner: L. Samir
tags:
  - performance
former-id: TC-GG3KNA
parent: REQ-K6FGAY0
order: b1J
links:
  - type: verifies
    target: REQ-FF77ZPP
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
