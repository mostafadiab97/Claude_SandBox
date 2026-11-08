---
id: REQ-Q8QCP3Q
type: test-case
title: "Verify: Over-temperature monitor logs the connection state"
status: Draft
owner: M. Farouk
tags:
  - regulatory
  - accessibility
  - performance
former-id: TC-XFNW97
parent: REQ-K6FGAY0
order: a6
links:
  - type: verifies
    target: REQ-YCQG7EF
    confirmed: c4c96610c247
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Report schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
