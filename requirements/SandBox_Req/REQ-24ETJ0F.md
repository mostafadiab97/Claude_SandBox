---
id: REQ-24ETJ0F
type: test-case
title: "Verify: Bluetooth LE link measures audit records"
status: Approved
priority: Medium
owner: J. Müller
former-id: TC-V698SN
parent: REQ-67RQXCK
order: b0r
links:
  - type: verifies
    target: REQ-J216NC7
    confirmed: 5bd6f55bad83
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Synchronise relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
