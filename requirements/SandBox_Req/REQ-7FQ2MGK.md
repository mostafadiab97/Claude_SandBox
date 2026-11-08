---
id: REQ-7FQ2MGK
type: test-case
title: "Verify: Pairing process detects user preferences"
status: Approved
owner: L. Samir
former-id: TC-63DY56
parent: REQ-67RQXCK
order: b1N
links:
  - type: verifies
    target: REQ-31049SN
    confirmed: "025545e52884"
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Validate firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
