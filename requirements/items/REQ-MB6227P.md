---
id: REQ-MB6227P
type: test-case
title: "Verify: Bluetooth LE link synchronises the set point"
status: Approved
tags:
  - release-2.0
former-id: TC-A2WYHP
parent: REQ-67RQXCK
order: b0q
links:
  - type: verifies
    target: REQ-NAKKA1A
    confirmed: aca44262add5
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Measure access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
