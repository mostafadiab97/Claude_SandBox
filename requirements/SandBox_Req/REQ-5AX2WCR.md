---
id: REQ-5AX2WCR
type: test-case
title: "Verify: Zigbee radio measures the operating mode"
status: Approved
priority: Medium
former-id: TC-X9P5F4
parent: REQ-67RQXCK
order: b1L
links:
  - type: verifies
    target: REQ-VARSTZG
    confirmed: c915b489dd1f
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
