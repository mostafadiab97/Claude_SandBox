---
id: TC-X2D3JE
type: test-case
title: "Verify: Login screen validates audit records"
status: Review
priority: Medium
owner: M. Farouk
tags:
  - regulatory
  - safety
parent: INFO-J0FETE
order: 1510
links:
  - type: verifies
    target: SYS-3TWJPP
  - type: verifies
    target: SW-A10E8C
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 20 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Store relay events and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
