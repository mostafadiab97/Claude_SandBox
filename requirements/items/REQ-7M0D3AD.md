---
id: REQ-7M0D3AD
type: test-case
title: "Verify: Bluetooth LE link measures sensor readings"
status: Approved
priority: Medium
owner: N. Kamal
tags:
  - cost
  - security
former-id: TC-VAJSZT
parent: REQ-67RQXCK
order: ab
links:
  - type: verifies
    target: REQ-PYT4632
    confirmed: 05e0bb495f40
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Calibrate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
