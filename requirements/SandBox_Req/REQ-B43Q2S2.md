---
id: REQ-B43Q2S2
type: test-case
title: "Verify: Bluetooth LE link stores firmware images"
status: Draft
owner: Y. Saber
tags:
  - connectivity
  - ux
former-id: TC-2ZFGW1
parent: REQ-67RQXCK
order: aR
links:
  - type: verifies
    target: REQ-PKDYEYJ
    confirmed: 05248eb02fec
---
**Objective:** verify that the Bluetooth LE link behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the Bluetooth LE link with default settings.
2. Restore error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
