---
id: REQ-8BHJE76
type: test-case
title: "Verify: Pairing process measures audit records"
status: Approved
priority: Medium
owner: Y. Saber
former-id: TC-1N848H
parent: REQ-67RQXCK
order: b0M
links:
  - type: verifies
    target: REQ-3EZE86Y
    confirmed: bc98487a5cdc
  - type: verifies
    target: REQ-7C91C22
    confirmed: 0210b675a2d9
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Restore the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
