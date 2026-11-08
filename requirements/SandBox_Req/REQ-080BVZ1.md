---
id: REQ-080BVZ1
type: test-case
title: "Regression: Schedule editor encrypts energy consumption"
status: Obsolete
priority: High
owner: Y. Saber
former-id: TC-TZWW7W
parent: REQ-6H15AV2
order: b0e
links:
  - type: verifies
    target: REQ-M6ARR9M
    confirmed: b92b84803641
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Detect firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
