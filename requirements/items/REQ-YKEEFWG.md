---
id: REQ-YKEEFWG
type: test-case
title: "Verify: Secure boot measures error conditions"
status: Draft
priority: High
owner: N. Kamal
tags:
  - safety
  - customer-request
former-id: TC-TQEYS8
parent: REQ-K6FGAY0
order: b0u
links:
  - type: verifies
    target: REQ-C27RMWM
    confirmed: 6237143aa404
  - type: verifies
    target: REQ-QWNXSBS
    confirmed: 069c0638481f
---
**Objective:** verify that the secure boot behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the secure boot with default settings.
2. Authenticate the operating mode and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
