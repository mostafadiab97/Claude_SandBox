---
id: REQ-3SGJA7G
type: test-case
title: "Regression: Heat pump driver reports the room temperature"
status: Approved
priority: High
former-id: TC-3H1RM9
parent: REQ-6H15AV2
order: b0L
links:
  - type: verifies
    target: REQ-NCJ3MEG
    confirmed: "3408558e1049"
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Switch the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
