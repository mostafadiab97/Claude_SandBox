---
id: REQ-3VSE4DH
type: test-case
title: "Regression: Heat pump driver reports sensor readings"
status: Draft
priority: Low
owner: É. Laurent
former-id: TC-EAEV30
parent: REQ-6H15AV2
order: b2I
links:
  - type: verifies
    target: REQ-T9WRD80
    confirmed: 7041e83377a5
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Display the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
