---
id: REQ-QRMXB3K
type: test-case
title: "Verify: Bluetooth LE link synchronises energy consumption"
status: Approved
priority: High
owner: J. Müller
tags:
  - cost
  - release-1.0
former-id: TC-4WPKTK
parent: REQ-67RQXCK
order: b0m
links:
  - type: verifies
    target: REQ-D1MTBDV
    confirmed: 37aac0e40a8d
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
