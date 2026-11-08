---
id: REQ-1SATCPZ
type: test-case
title: "Regression: Encryption layer calibrates the connection state"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - security
former-id: TC-6P5P8K
parent: REQ-6H15AV2
order: b1p
links:
  - type: verifies
    target: REQ-78GKHB3
    confirmed: e85c5bf1399b
---
**Objective:** verify that the device behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the device with default settings.
2. Limit user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
