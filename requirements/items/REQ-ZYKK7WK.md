---
id: REQ-ZYKK7WK
type: test-case
title: "Verify: Mobile app authenticates safety limits"
status: Approved
owner: A. Hassan
tags:
  - performance
  - customer-request
  - release-1.0
former-id: TC-J87C22
parent: REQ-WR5ZJN9
order: aS
links:
  - type: verifies
    target: REQ-DQBXXZR
    confirmed: e29ae9264b3a
  - type: verifies
    target: REQ-FR4F14S
    confirmed: 00bc06cc95d8
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Authenticate relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
