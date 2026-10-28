---
id: REQ-DP1DFEH
type: test-case
title: "Verify: Bluetooth LE link detects access tokens"
status: Approved
priority: High
owner: M. Farouk
former-id: TC-TPS5MK
parent: REQ-67RQXCK
order: b0G
links:
  - type: verifies
    target: REQ-AQ8M0XJ
    confirmed: 9597e83a664b
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Store audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
