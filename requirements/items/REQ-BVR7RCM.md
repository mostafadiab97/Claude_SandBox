---
id: REQ-BVR7RCM
type: test-case
title: "Verify: Over-temperature monitor logs access tokens"
status: Obsolete
priority: High
owner: É. Laurent
former-id: TC-BZM3TM
parent: REQ-K6FGAY0
order: ao
links:
  - type: verifies
    target: REQ-7XBRPQY
    confirmed: 37b1ff049bc6
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Log error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
