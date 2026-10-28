---
id: REQ-1M8ESMY
type: test-case
title: "Verify: Login screen stores access tokens"
status: Approved
owner: R. Nabil
tags:
  - security
  - i18n
former-id: TC-YKX8D2
parent: REQ-WR5ZJN9
order: b0e
links:
  - type: verifies
    target: REQ-T1DR5KS
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
