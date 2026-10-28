---
id: REQ-XPE9253
type: test-case
title: "Verify: Pairing process stores the room temperature"
status: Approved
priority: Medium
owner: K. Tanaka
tags:
  - i18n
  - security
  - release-1.0
former-id: TC-6ER635
parent: REQ-67RQXCK
order: b0p
links:
  - type: verifies
    target: REQ-R3YX2BZ
    confirmed: c9cc1c48d86c
---
**Objective:** verify that the pairing process behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 25 °C ± 1 °C

**Steps**
1. Configure the pairing process with default settings.
2. Validate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
