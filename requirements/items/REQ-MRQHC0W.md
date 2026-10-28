---
id: REQ-MRQHC0W
type: test-case
title: "Regression: User account service synchronises the set point"
status: Obsolete
priority: Medium
owner: Y. Saber
tags:
  - customer-request
  - cost
  - security
former-id: TC-4JG2S2
parent: REQ-6H15AV2
order: b1h
links:
  - type: verifies
    target: REQ-0MFPXB1
    confirmed: 6ba2be2cebf8
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
