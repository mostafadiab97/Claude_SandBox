---
id: TC-YKX8D2
type: test-case
title: "Verify: Login screen stores access tokens"
status: Approved
owner: R. Nabil
tags:
  - security
  - i18n
parent: INFO-J0FETE
order: 1030
links:
  - type: verifies
    target: SYS-72TJ12
    confirmed: f925a1940bd6
---
**Objective:** verify that the login screen behaves as specified.

**Preconditions**
- Device powered and paired with the test account
- Ambient temperature 23 °C ± 1 °C

**Steps**
1. Configure the login screen with default settings.
2. Calibrate humidity values and record the result.
3. Repeat 10 times.

**Expected result:** all 10 runs pass the acceptance criteria of the verified requirement.
