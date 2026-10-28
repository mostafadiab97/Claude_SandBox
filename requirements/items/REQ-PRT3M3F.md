---
id: REQ-PRT3M3F
type: test-case
title: "Verify: Encryption layer switchs schedule entries"
status: Review
priority: High
tags:
  - safety
  - performance
former-id: TC-48J29E
parent: REQ-K6FGAY0
order: as
links:
  - type: verifies
    target: REQ-0C64JCK
    confirmed: 83d1b44e122c
  - type: verifies
    target: REQ-06TSPA6
    confirmed: da50ffeb4c30
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Synchronise user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
