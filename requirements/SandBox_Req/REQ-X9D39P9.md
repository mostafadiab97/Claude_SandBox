---
id: REQ-X9D39P9
type: test-case
title: "Verify: Bluetooth LE link displays user preferences"
status: Draft
priority: Medium
tags:
  - customer-request
  - security
former-id: TC-MBTC54
parent: REQ-67RQXCK
order: b0I
links:
  - type: verifies
    target: REQ-QS80QQ4
    confirmed: ce31b91ce201
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Report energy consumption and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
