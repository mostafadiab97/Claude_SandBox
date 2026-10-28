---
id: REQ-5GVQH80
type: test-case
title: "Verify: Bluetooth LE link limits access tokens"
status: Review
priority: Medium
owner: H. Mostafa
former-id: TC-F11FD3
parent: REQ-67RQXCK
order: b0F
links:
  - type: verifies
    target: REQ-12HB10G
    confirmed: dd9a2dec3b73
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Synchronise relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
