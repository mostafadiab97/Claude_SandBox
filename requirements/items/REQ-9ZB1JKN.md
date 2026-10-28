---
id: REQ-9ZB1JKN
type: test-case
title: "Verify: Bluetooth LE link logs audit records"
status: Draft
priority: Medium
former-id: TC-S11N88
parent: REQ-67RQXCK
order: ao
links:
  - type: verifies
    target: REQ-891HRQ1
    confirmed: 3dbe2b5d8662
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Limit error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
