---
id: REQ-RYBSJMS
type: test-case
title: "Verify: Local API detects firmware images"
status: Approved
priority: Medium
owner: R. Nabil
tags:
  - security
  - i18n
  - regulatory
former-id: TC-6XBEFK
parent: REQ-67RQXCK
order: b0n
links:
  - type: verifies
    target: REQ-SN84PTN
    confirmed: c0e6f0c26e10
  - type: verifies
    target: REQ-NYRKJZW
    confirmed: 9ce59d80eec7
---
**Objective:** verify that the local API behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the local API with default settings.
2. Validate the set point and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
