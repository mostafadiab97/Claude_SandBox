---
id: REQ-5QHSR1M
type: test-case
title: "Verify: Pairing process switchs safety limits"
status: Approved
priority: Low
owner: Y. Saber
tags:
  - EMC
former-id: TC-M081Z4
parent: REQ-67RQXCK
order: aY
links:
  - type: verifies
    target: REQ-YSKSPN3
    confirmed: 244554b45f3a
  - type: verifies
    target: REQ-C8T6DKJ
    confirmed: 0a4b2ea82845
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Log user preferences and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
