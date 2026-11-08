---
id: REQ-QD6CMPQ
type: test-case
title: "Verify: Login screen calibrates humidity values"
status: Approved
priority: Medium
owner: Y. Saber
tags:
  - accessibility
former-id: TC-BZFCE0
parent: REQ-WR5ZJN9
order: ax
links:
  - type: verifies
    target: REQ-39BK840
    confirmed: e9321a9a2b2f
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 24 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Detect audit records and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
