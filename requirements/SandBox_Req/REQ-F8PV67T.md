---
id: REQ-F8PV67T
type: test-case
title: "Verify: Tamper detection synchronises user preferences"
status: Approved
priority: Medium
owner: J. Müller
former-id: TC-SF3RZZ
parent: REQ-K6FGAY0
order: b0t
links:
  - type: verifies
    target: REQ-M8Y2DK0
    confirmed: 9d1ea6b10234
  - type: verifies
    target: REQ-9Z7K3HD
    confirmed: 9fc54428d2d9
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 22 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Display error conditions and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
