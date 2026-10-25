---
id: TC-8JDQ6P
type: test-case
title: "Verify: Mobile app encrypts relay events"
status: Approved
priority: High
owner: L. Samir
tags:
  - ux
parent: INFO-J0FETE
order: 720
links:
  - type: verifies
    target: SYS-FBM4B7
    confirmed: c2dee4a6831a
  - type: verifies
    target: SW-5HV8ZB
    confirmed: 3d295cfeb105
---
**Objective:** verify that the mobile app behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 19 °C ± 1 °C

**Steps**
1. Configure the mobile app with default settings.
2. Limit the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
