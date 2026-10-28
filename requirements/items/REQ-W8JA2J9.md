---
id: REQ-W8JA2J9
type: test-case
title: "Verify: Pairing process validates access tokens"
status: Review
priority: High
owner: R. Nabil
tags:
  - power
former-id: TC-0PKAMZ
parent: REQ-67RQXCK
order: aL
links:
  - type: verifies
    target: REQ-PR70XPC
    confirmed: 2a3acc022feb
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Synchronise sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
