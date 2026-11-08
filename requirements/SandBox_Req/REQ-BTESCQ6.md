---
id: REQ-BTESCQ6
type: test-case
title: "Verify: Relay board switchs schedule entries"
status: Draft
priority: High
owner: A. Hassan
former-id: TC-R1JH7F
parent: REQ-F9Z1FYS
order: b0T
links:
  - type: verifies
    target: REQ-SQ5X7CQ
    confirmed: 85f6bb475fe2
  - type: verifies
    target: REQ-DXBCVRY
    confirmed: cbc211e398ee
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Encrypt the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
