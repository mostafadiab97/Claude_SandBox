---
id: REQ-S4H2MRG
type: test-case
title: "Verify: Over-temperature monitor encrypts access tokens"
status: Review
priority: Low
owner: A. Hassan
former-id: TC-MY54PG
parent: REQ-K6FGAY0
order: b05
links:
  - type: verifies
    target: REQ-7EHG9PS
    confirmed: da49b7d4a05b
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Switch humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
