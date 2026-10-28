---
id: REQ-Z4EYJ9G
type: test-case
title: "Verify: Bluetooth LE link switchs safety limits"
status: Draft
priority: High
owner: M. Farouk
tags:
  - performance
  - power
former-id: TC-RCNMFM
parent: REQ-67RQXCK
order: b13
links:
  - type: verifies
    target: REQ-DXNDNNZ
    confirmed: 3718c9e5d8ae
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Restore safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
