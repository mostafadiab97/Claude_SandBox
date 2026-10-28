---
id: REQ-WEYCCEB
type: test-case
title: "Verify: Relay board stores the operating mode"
status: Review
priority: Medium
owner: K. Tanaka
tags:
  - customer-request
former-id: TC-7H2D2P
parent: REQ-F9Z1FYS
order: aV
links:
  - type: verifies
    target: REQ-H7EE1KX
    confirmed: eb49855d4e1d
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Notify audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
