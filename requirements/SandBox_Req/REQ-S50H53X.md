---
id: REQ-S50H53X
type: test-case
title: "Verify: Bluetooth LE link measures sensor readings"
status: Approved
priority: Medium
owner: L. Samir
tags:
  - regulatory
former-id: TC-TEWJ6D
parent: REQ-67RQXCK
order: aZ
links:
  - type: verifies
    target: REQ-93GSKTC
    confirmed: f6e72f885951
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Detect schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
