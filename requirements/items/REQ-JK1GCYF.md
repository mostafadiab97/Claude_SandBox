---
id: REQ-JK1GCYF
type: test-case
title: "Verify: Local API authenticates safety limits"
status: Approved
priority: Low
owner: H. Mostafa
former-id: TC-PH7DAY
parent: REQ-67RQXCK
order: ap
links:
  - type: verifies
    target: REQ-0WQ07SG
    confirmed: ba8e9786a00b
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Report error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
