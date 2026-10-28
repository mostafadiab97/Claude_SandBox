---
id: REQ-JCTKC9P
type: test-case
title: "Verify: Status LED validates audit records"
status: Review
owner: Y. Saber
tags:
  - customer-request
  - ux
former-id: TC-4TVWBK
parent: REQ-Y9VHHKA
order: b1A
links:
  - type: verifies
    target: REQ-Q14ETWF
    confirmed: 02e2558f5021
  - type: verifies
    target: REQ-S2WSAFK
    confirmed: 76bbdf417470
---
**Objective:** verify that the status LED behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the status LED with default settings.
2. Restore audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
