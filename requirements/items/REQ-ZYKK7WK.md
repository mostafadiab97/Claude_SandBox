---
id: TC-J87C22
type: test-case
title: "Verify: Mobile app authenticates safety limits"
status: Approved
owner: A. Hassan
tags:
  - performance
  - customer-request
  - release-1.0
parent: INFO-J0FETE
order: 290
links:
  - type: verifies
    target: SYS-CRRCSR
    confirmed: e29ae9264b3a
  - type: verifies
    target: SW-57FCES
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
