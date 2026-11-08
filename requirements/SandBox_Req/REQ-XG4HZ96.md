---
id: REQ-XG4HZ96
type: test-case
title: "Verify: Encryption layer logs audit records"
status: Review
owner: J. Müller
tags:
  - release-1.0
former-id: TC-TEB88Z
parent: REQ-K6FGAY0
order: aj
links:
  - type: verifies
    target: REQ-4Q67RJE
    confirmed: ff14b57eee23
  - type: verifies
    target: REQ-R3R7FXA
    confirmed: e5166e8743b5
---
**Objective:** verify that the encryption layer behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the encryption layer with default settings.
2. Encrypt sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
