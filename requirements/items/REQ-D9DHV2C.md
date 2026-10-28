---
id: REQ-D9DHV2C
type: test-case
title: "Verify: Relay board notifys humidity values"
status: Approved
priority: Medium
owner: محمد علي
former-id: TC-96Y7QR
parent: REQ-F9Z1FYS
order: b0r
links:
  - type: verifies
    target: REQ-RP73624
    confirmed: 0ac53f80c216
  - type: verifies
    target: REQ-EKMKFZ6
    confirmed: d8fdea0c8e00
---
**Objective:** verify that the relay board behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the relay board with default settings.
2. Measure the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
