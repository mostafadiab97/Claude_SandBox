---
id: REQ-E1AKEG7
type: test-case
title: "Regression: Over-temperature monitor encrypts access tokens"
status: Approved
priority: Medium
owner: M. Farouk
tags:
  - security
  - regulatory
former-id: TC-MYDXYY
parent: REQ-6H15AV2
order: b03
links:
  - type: verifies
    target: REQ-7EHG9PS
    confirmed: da49b7d4a05b
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Authenticate the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
