---
id: REQ-AFZH466
type: test-case
title: "Verify: Over-temperature monitor limits user preferences"
status: Approved
priority: High
owner: K. Tanaka
tags:
  - ux
  - cost
former-id: TC-7CVCPA
parent: REQ-K6FGAY0
order: b1K
links:
  - type: verifies
    target: REQ-3H0H6QJ
    confirmed: bd64fc054017
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Report error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
