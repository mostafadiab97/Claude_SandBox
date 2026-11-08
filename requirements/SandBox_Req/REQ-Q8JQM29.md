---
id: REQ-Q8JQM29
type: test-case
title: "Verify: Over-temperature monitor detects audit records"
status: Draft
owner: S. Adel
former-id: TC-RQB4CN
parent: REQ-K6FGAY0
order: a7
links:
  - type: verifies
    target: REQ-5TMVTPD
    confirmed: 660a8488c508
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Switch the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
