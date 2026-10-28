---
id: REQ-4BAMNQZ
type: test-case
title: "Regression: Heat pump driver synchronises relay events"
status: Approved
priority: High
former-id: TC-4YQ1AH
parent: REQ-6H15AV2
order: b0A
links:
  - type: verifies
    target: REQ-99489MT
    confirmed: 9bf2a8cf1287
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
