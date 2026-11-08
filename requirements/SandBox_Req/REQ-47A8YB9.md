---
id: REQ-47A8YB9
type: test-case
title: "Verify: Tamper detection restores the connection state"
status: Approved
tags:
  - customer-request
  - regulatory
former-id: TC-PPV4GZ
parent: REQ-K6FGAY0
order: aF
links:
  - type: verifies
    target: REQ-RB03G7X
    confirmed: fada4baa41ba
  - type: verifies
    target: REQ-GRMS05G
    confirmed: ea080242c245
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Encrypt humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
