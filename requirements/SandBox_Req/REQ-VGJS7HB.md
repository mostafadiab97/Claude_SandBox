---
id: REQ-VGJS7HB
type: test-case
title: "Verify: Home dashboard notifys the connection state"
status: Approved
priority: High
owner: L. Samir
tags:
  - power
former-id: TC-MPJ2E9
parent: REQ-WR5ZJN9
order: b03
links:
  - type: verifies
    target: REQ-S6ZH8XQ
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
