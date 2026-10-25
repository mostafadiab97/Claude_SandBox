---
id: TC-PPV4GZ
type: test-case
title: "Verify: Tamper detection restores the connection state"
status: Approved
tags:
  - customer-request
  - regulatory
parent: INFO-Z4TW4B
order: 160
links:
  - type: verifies
    target: SYS-ABZP07
    confirmed: fada4baa41ba
  - type: verifies
    target: SW-1VRPBQ
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
