---
id: REQ-WP5XHSE
type: test-case
title: "Verify: Over-temperature monitor limits sensor readings"
status: Approved
owner: H. Mostafa
former-id: TC-4FM2JJ
parent: REQ-K6FGAY0
order: b0L
links:
  - type: verifies
    target: REQ-QFZ1F36
    confirmed: 720362ab5cfe
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Measure audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
