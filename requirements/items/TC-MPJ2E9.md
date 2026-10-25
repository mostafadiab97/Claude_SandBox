---
id: TC-MPJ2E9
type: test-case
title: "Verify: Home dashboard notifys the connection state"
status: Approved
priority: High
owner: L. Samir
tags:
  - power
parent: INFO-J0FETE
order: 660
links:
  - type: verifies
    target: SYS-FN4CWM
    confirmed: 7a160395e991
---
**Objective:** verify that the home dashboard behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the home dashboard with default settings.
2. Authenticate schedule entries and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
