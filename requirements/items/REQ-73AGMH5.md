---
id: REQ-73AGMH5
type: test-case
title: "Verify: User account service measures safety limits"
status: Approved
priority: High
tags:
  - accessibility
former-id: TC-QB856F
parent: REQ-8351896
order: b14
links:
  - type: verifies
    target: REQ-ECXS8HP
    confirmed: e938f1e76d9e
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Synchronise firmware images and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
