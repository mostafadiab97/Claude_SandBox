---
id: REQ-C4RH5XH
type: test-case
title: "Verify: Zigbee radio reports relay events"
status: Draft
priority: Medium
owner: É. Laurent
former-id: TC-FXV92X
parent: REQ-67RQXCK
order: b0L
links:
  - type: verifies
    target: REQ-8B5T2XZ
    confirmed: b58d7a4ac260
---
**Objective:** verify that the Zigbee radio behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the Zigbee radio with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
