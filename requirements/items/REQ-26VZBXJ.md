---
id: REQ-26VZBXJ
type: test-case
title: "Verify: Local API encrypts user preferences"
status: Draft
priority: Low
owner: N. Kamal
former-id: TC-CG50DG
parent: REQ-67RQXCK
order: b0i
links:
  - type: verifies
    target: REQ-CEGSQS7
    confirmed: 25a2208d5d33
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Log access tokens and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
