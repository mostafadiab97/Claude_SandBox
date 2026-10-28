---
id: REQ-H84XFPH
type: test-case
title: "Verify: Encryption layer switchs the room temperature"
status: Obsolete
priority: High
owner: É. Laurent
tags:
  - EMC
  - security
former-id: TC-NMR3WN
parent: REQ-K6FGAY0
order: b0J
links:
  - type: verifies
    target: REQ-FN2JXAS
    confirmed: eea34ba9a0b3
  - type: verifies
    target: REQ-S69QE64
    confirmed: 81a7bc4043b2
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Measure relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
