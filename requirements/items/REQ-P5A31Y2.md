---
id: REQ-P5A31Y2
type: test-case
title: "Verify: Relay board displays the connection state"
status: Approved
priority: Medium
owner: M. Farouk
former-id: TC-TZKBDN
parent: REQ-F9Z1FYS
order: aj
links:
  - type: verifies
    target: REQ-WQSDQ95
    confirmed: 5a5dbeacc343
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
