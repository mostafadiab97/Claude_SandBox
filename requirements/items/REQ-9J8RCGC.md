---
id: REQ-9J8RCGC
type: test-case
title: "Verify: Pairing process measures safety limits"
status: Approved
priority: High
owner: É. Laurent
tags:
  - customer-request
  - accessibility
  - regulatory
former-id: TC-WZ6XG2
parent: REQ-67RQXCK
order: b0z
links:
  - type: verifies
    target: REQ-M3BR6KY
    confirmed: cda235c01515
  - type: verifies
    target: REQ-1VRMR6D
    confirmed: 0f3b5272ad4b
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Validate access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
