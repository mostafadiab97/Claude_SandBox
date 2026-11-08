---
id: REQ-ST8AQ1X
type: test-case
title: "Verify: Pairing process notifys the connection state"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - customer-request
  - ux
  - connectivity
former-id: TC-FE2FJZ
parent: REQ-67RQXCK
order: b0a
links:
  - type: verifies
    target: REQ-0HP2Y9D
    confirmed: 777482c845de
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Restore the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
