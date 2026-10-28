---
id: REQ-14KGVP5
type: test-case
title: "Verify: Local API switchs firmware images"
status: Draft
priority: Medium
owner: É. Laurent
former-id: TC-1W7PCE
parent: REQ-67RQXCK
order: b0s
links:
  - type: verifies
    target: REQ-9FPN2X9
    confirmed: 40dbdbb8a1de
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Notify safety limits and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
