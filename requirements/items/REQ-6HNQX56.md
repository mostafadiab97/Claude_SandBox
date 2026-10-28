---
id: REQ-6HNQX56
type: test-case
title: "Regression: OTA server switchs the operating mode"
status: Obsolete
priority: Medium
former-id: TC-WF2GXD
parent: REQ-6H15AV2
order: b1z
links:
  - type: verifies
    target: REQ-D6CAXH8
    confirmed: 45d68bfca0bb
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
