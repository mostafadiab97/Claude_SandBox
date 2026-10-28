---
id: REQ-J36HTVV
type: test-case
title: "Verify: Over-temperature monitor synchronises firmware images"
status: Draft
priority: Low
owner: L. Samir
former-id: TC-4AM1F6
parent: REQ-K6FGAY0
order: ag
links:
  - type: verifies
    target: REQ-QXZYXCA
    confirmed: 64d198139b67
---
**Objective:** verify that the over-temperature monitor behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the over-temperature monitor with default settings.
2. Validate error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
