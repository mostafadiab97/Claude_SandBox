---
id: REQ-59AYZY5
type: test-case
title: "Verify: Watchdog measures sensor readings"
status: Draft
tags:
  - regulatory
  - connectivity
  - performance
former-id: TC-SSD9BK
parent: REQ-K6FGAY0
order: a4
links:
  - type: verifies
    target: REQ-B0PGH7P
    confirmed: 4c75da355236
  - type: verifies
    target: REQ-P7GSJF8
    confirmed: 61e860ae008f
---
**Objective:** verify that the watchdog behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the watchdog with default settings.
2. Measure firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
