---
id: REQ-8E7ASCA
type: test-case
title: "Verify: Bluetooth LE link measures the operating mode"
status: Review
priority: Medium
owner: M. Farouk
tags:
  - release-2.0
former-id: TC-RD0RYP
parent: REQ-67RQXCK
order: am
links:
  - type: verifies
    target: REQ-AYCB30Y
    confirmed: 8fcf329b307d
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Log sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
