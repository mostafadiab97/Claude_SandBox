---
id: TC-MX0Y8C
type: test-case
title: "Verify: Login screen logs energy consumption"
status: Obsolete
owner: L. Samir
tags:
  - security
  - safety
parent: INFO-J0FETE
order: 1550
links:
  - type: verifies
    target: SYS-781NXX
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 21 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Notify the connection state and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
