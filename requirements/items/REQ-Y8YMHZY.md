---
id: REQ-Y8YMHZY
type: test-case
title: "Regression: Login screen switchs firmware images"
status: Approved
priority: High
owner: M. Farouk
tags:
  - connectivity
  - safety
  - accessibility
former-id: TC-0GN10Q
parent: REQ-6H15AV2
order: b1K
links:
  - type: verifies
    target: REQ-TDS2MHG
    confirmed: 072f7558d179
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Encrypt the room temperature and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
