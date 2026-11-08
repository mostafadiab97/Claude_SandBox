---
id: REQ-G4MA49E
type: test-case
title: "Verify: Over-temperature monitor restores the operating mode"
status: Draft
priority: Low
owner: K. Tanaka
tags:
  - regulatory
  - cost
former-id: TC-6AVKS1
parent: REQ-K6FGAY0
order: an
links:
  - type: verifies
    target: REQ-X6GGVEP
    confirmed: 215aef7ef123
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Encrypt safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
