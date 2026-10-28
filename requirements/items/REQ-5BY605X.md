---
id: REQ-5BY605X
type: test-case
title: "Verify: Local API validates the connection state"
status: Review
priority: High
owner: محمد علي
former-id: TC-0GJ0PZ
parent: REQ-67RQXCK
order: aB
links:
  - type: verifies
    target: REQ-BNSVZ8R
    confirmed: b3432a56f6cd
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Limit relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
