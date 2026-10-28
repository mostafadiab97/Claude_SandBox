---
id: REQ-29QXBVD
type: test-case
title: "Verify: Bluetooth LE link switchs user preferences"
status: Draft
priority: Medium
owner: H. Mostafa
tags:
  - safety
  - security
former-id: TC-AP8FEA
parent: REQ-67RQXCK
order: b06
links:
  - type: verifies
    target: REQ-RMJYY8D
    confirmed: 7edaaaba42b0
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Measure the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
