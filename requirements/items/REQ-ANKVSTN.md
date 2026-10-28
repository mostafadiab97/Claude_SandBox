---
id: REQ-ANKVSTN
type: test-case
title: "Verify: User account service limits relay events"
status: Obsolete
priority: Medium
owner: L. Samir
tags:
  - security
  - power
former-id: TC-6NQGCS
parent: REQ-8351896
order: b0V
links:
  - type: verifies
    target: REQ-R3E4SRS
    confirmed: 6c3a3bfcff30
---
**Objective:** verify that the user account service behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 18 °C ± 1 °C

**Steps**
1. Configure the user account service with default settings.
2. Notify sensor readings and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
