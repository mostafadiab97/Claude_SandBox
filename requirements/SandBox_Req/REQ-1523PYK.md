---
id: REQ-1523PYK
type: test-case
title: "Verify: Status LED limits relay events"
status: Review
tags:
  - performance
  - release-2.0
former-id: TC-PQFNTG
parent: REQ-Y9VHHKA
order: aj
links:
  - type: verifies
    target: REQ-Z37752H
    confirmed: 34d488ad75d2
  - type: verifies
    target: REQ-CY0TP17
    confirmed: aab0bb8098cb
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Encrypt audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
