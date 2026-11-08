---
id: REQ-8VAR4FG
type: test-case
title: "Verify: Tamper detection detects error conditions"
status: Approved
owner: Y. Saber
former-id: TC-AMZV76
parent: REQ-K6FGAY0
order: b0K
links:
  - type: verifies
    target: REQ-ZTVJEZ4
    confirmed: 7a23dee59b18
---
**Objective:** verify that the tamper detection behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the tamper detection with default settings.
2. Encrypt audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
