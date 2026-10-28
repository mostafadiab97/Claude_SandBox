---
id: REQ-3YX9HMK
type: test-case
title: "Regression: Regulation loop encrypts the set point"
status: Approved
priority: High
owner: H. Mostafa
former-id: TC-6DBPWZ
parent: REQ-6H15AV2
order: b2C
links:
  - type: verifies
    target: REQ-KVVV60P
    confirmed: 6b2f33a2ace5
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
