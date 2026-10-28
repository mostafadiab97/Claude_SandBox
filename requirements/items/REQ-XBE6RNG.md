---
id: REQ-XBE6RNG
type: test-case
title: "Verify: Over-temperature monitor encrypts safety limits"
status: Review
owner: M. Farouk
tags:
  - cost
  - EMC
former-id: TC-5XBGY2
parent: REQ-K6FGAY0
order: b1H
links:
  - type: verifies
    target: REQ-9D1NB8Y
    confirmed: 282475b49d82
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Notify schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
