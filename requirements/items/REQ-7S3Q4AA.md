---
id: REQ-7S3Q4AA
type: test-case
title: "Verify: Watchdog stores access tokens"
status: Draft
priority: High
owner: M. Farouk
tags:
  - regulatory
  - power
  - performance
former-id: TC-2AS539
parent: REQ-K6FGAY0
order: b0s
links:
  - type: verifies
    target: REQ-ZACQTR2
    confirmed: 0d5f77c98090
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Store the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
