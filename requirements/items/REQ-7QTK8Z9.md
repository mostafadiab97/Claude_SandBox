---
id: REQ-7QTK8Z9
type: test-case
title: "Verify: Bluetooth LE link measures schedule entries"
status: Approved
owner: R. Nabil
tags:
  - customer-request
former-id: TC-FRZ10E
parent: REQ-67RQXCK
order: aU
links:
  - type: verifies
    target: REQ-9WKYQ5Q
    confirmed: fca3f3673c34
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Encrypt humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
