---
id: REQ-PWNGY5K
type: test-case
title: "Regression: Schedule editor measures sensor readings"
status: Approved
former-id: TC-NEJH0E
parent: REQ-6H15AV2
order: b0m
links:
  - type: verifies
    target: REQ-FF5B6MJ
    confirmed: 088ced33b5bc
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Synchronise the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
