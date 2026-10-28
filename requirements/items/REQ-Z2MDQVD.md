---
id: REQ-Z2MDQVD
type: test-case
title: "Verify: Tamper detection limits audit records"
status: Approved
owner: Y. Saber
tags:
  - EMC
  - cost
  - ux
former-id: TC-BT8QQ0
parent: REQ-K6FGAY0
order: ae
links:
  - type: verifies
    target: REQ-KVE2D34
    confirmed: cd9c225e18ad
  - type: verifies
    target: REQ-ZMZXPZA
    confirmed: ab37a081d370
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Switch the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
