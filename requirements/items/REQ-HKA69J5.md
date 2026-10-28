---
id: REQ-HKA69J5
type: test-case
title: "Verify: Tamper detection synchronises firmware images"
status: Approved
priority: Low
tags:
  - safety
former-id: TC-6KR06F
parent: REQ-K6FGAY0
order: b16
links:
  - type: verifies
    target: REQ-CZVE4E4
    confirmed: 4ea3d699c52a
  - type: verifies
    target: REQ-EERHB6H
    confirmed: 5d785516a115
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Encrypt the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
