---
id: REQ-FJMVP09
type: test-case
title: "Verify: Local API restores firmware images"
status: Approved
owner: Y. Saber
tags:
  - customer-request
  - release-1.0
  - release-2.0
former-id: TC-JWG6R0
parent: REQ-67RQXCK
order: b04
links:
  - type: verifies
    target: REQ-63BDR23
    confirmed: 22452286eeb7
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Log the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
