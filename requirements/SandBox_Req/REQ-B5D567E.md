---
id: REQ-B5D567E
type: test-case
title: "Verify: Watchdog switchs safety limits"
status: Review
priority: High
owner: H. Mostafa
tags:
  - i18n
former-id: TC-C9F5TJ
parent: REQ-K6FGAY0
order: am
links:
  - type: verifies
    target: REQ-A84X06T
    confirmed: 13df4104599e
  - type: verifies
    target: REQ-8RSFWRX
    confirmed: baa32ece9812
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Synchronise user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
