---
id: REQ-K3Q94N7
type: test-case
title: "Verify: Status LED restores the room temperature"
status: Approved
priority: Medium
owner: A. Hassan
tags:
  - release-2.0
  - customer-request
former-id: TC-812KQQ
parent: REQ-Y9VHHKA
order: af
links:
  - type: verifies
    target: REQ-ND2B61F
    confirmed: 028b4e4661e2
  - type: verifies
    target: REQ-60ZFB33
    confirmed: dbe3045309c3
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Encrypt relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
